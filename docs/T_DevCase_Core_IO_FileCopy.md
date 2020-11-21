# FileCopy Class
 

Performs asynchronous file-copy operations with support for cancellation.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.FileCopy<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class FileCopy : AestheticObject, IDisposable
```

**VB**<br />
``` VB
Public Class FileCopy
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileCopy
```

**C++**<br />
``` C++
public ref class FileCopy : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
type FileCopy =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The FileCopy type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileCopy__ctor">FileCopy(FileInfo)</a></td><td>
Initializes a new instance of the FileCopy class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileCopy__ctor_1">FileCopy(String)</a></td><td>
Initializes a new instance of the FileCopy class.</td></tr></table>&nbsp;
<a href="#filecopy-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_FileCopy_File">File</a></td><td>
Gets the source file.</td></tr></table>&nbsp;
<a href="#filecopy-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileCopy_CancelCopy">CancelCopy</a></td><td>
Cancels a file-copy operation.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileCopy_CopyTo">CopyTo</a></td><td>
Asynchronously copies the source file to the specified destination.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileCopy_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileCopy_IsCanceled">IsCanceled</a></td><td>
Determines whether the specified file-copy task was cancelled.</td></tr></table>&nbsp;
<a href="#filecopy-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_IO_FileCopy_FileCopyProgressChanged">FileCopyProgressChanged</a></td><td>
Occurs when the progress of a file-copy operation has changed.</td></tr></table>&nbsp;
<a href="#filecopy-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#filecopy-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    Friend WithEvents FileCopier As FileCopy
    Private fileCopyCancelToken As CancellationTokenSource

    Private Sub Button1_Click() Handles Button1.Click

        Me.StartCopy()

    End Sub

    Private Sub Button2_Click() Handles Button2.Click

        Me.CancelCopy()

    End Sub

    Private Sub StartCopy()

        ' Create a dummy file of 2 GB
        Using fs As New FileStream("C:\source file.ext", FileMode.CreateNew)
            fs.SetLength(2147483648)
        End Using

        Me.FileCopier = New FileCopy("C:\source file.ext")

        Me.fileCopyCancelToken =
            Me.FileCopier.CopyTo("C:\Target file.ext",
                                 bufferSize:=(CInt(Me.FileCopier.File.Length \ (1024 * 100)) + 1),
                                 overwrite:=True,
                                 deleteFileOnCancel:=False,
                                 cancelCallback:=AddressOf Me.FileCopier_CancelCallBack)

    End Sub

    Private Sub CancelCopy()

        ' Cancel the current file-copy operation.
        Me.FileCopier.CancelCopy(Me.fileCopyCancelToken)

    End Sub

    ''' <summary>
    ''' Callback that is called when the a file-copy operation of the <see cref="FileCopier"/> is canceled.
    ''' </summary>
    Private Sub FileCopier_CancelCallBack()

        Me.Invoke(
            Sub()
                Me.Label1.Text = "Canceled!"
                Me.Label2.Text = "Canceled!"
                Me.Label3.Text = "Canceled!"
                Me.Label4.Text = "Canceled!"
            End Sub)
    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Handles the <see cref="FileCopy.FileCopyProgressChanged"/> event of the <see cref="FileCopier"/> instance.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <param name="sender">
    ''' The source of the event.
    ''' </param>
    ''' 
    ''' <param name="e">
    ''' The <see cref="FileCopyProgressChangedEventArgs"/> instance containing the event data.
    ''' </param>
    ''' ----------------------------------------------------------------------------------------------------
    Private Sub FileCopier_FileCopyProgressChanged(ByVal sender As Object, ByVal e As FileCopyProgressChangedEventArgs) _
    Handles FileCopier.FileCopyProgressChanged

        Me.Invoke(
            Sub()
                Me.Label1.Text = String.Format("Size: {0} MB", (e.Filesize / 1024).ToString("n2"))
                Me.Label2.Text = String.Format("Written: {0} MB", (e.BytesRead / 1024).ToString("n2"))
                Me.Label3.Text = String.Format("Read: {0} MB", (e.BytesRemaining / 1024).ToString("n2"))
                Me.Label4.Text = String.Format("Done: {0}%", e.Percentage.ToString("n2"))
            End Sub)

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />