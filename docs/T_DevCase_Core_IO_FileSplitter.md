# FileSplitter Class
 

Split or merge a file.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.FileSplitter<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class FileSplitter : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public Class FileSplitter
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileSplitter
```

**C++**<br />
``` C++
public ref class FileSplitter : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
type FileSplitter =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The FileSplitter type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileSplitter__ctor">FileSplitter</a></td><td>
Initializes a new instance of the FileSplitter class.</td></tr></table>&nbsp;
<a href="#filesplitter-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_FileSplitter_BufferSize">BufferSize</a></td><td>
Gets or sets the buffer size used to split or merge, in Bytes. 

 Default value is: <a href="T_DevCase_Core_IO_BufferSizes">Kb128</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_FileSplitter_File">File</a></td><td>
Gets the file to split or merge.</td></tr></table>&nbsp;
<a href="#filesplitter-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileSplitter_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileSplitter_Merge">Merge</a></td><td>
Merges the chunks of a previously splitted file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileSplitter_Split">Split(Int32, String, String, Boolean, Boolean)</a></td><td>
Splits a file into the specified amount of chunks.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileSplitter_Split_1">Split(Int64, String, String, Boolean, Boolean)</a></td><td>
Splits a file into chunks of the specified filesize.</td></tr></table>&nbsp;
<a href="#filesplitter-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_IO_FileSplitter_ProgressChanged">ProgressChanged</a></td><td>
Occurs when the progress changes when splitting or merging a file.</td></tr></table>&nbsp;
<a href="#filesplitter-class">Back to Top</a>

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
<a href="#filesplitter-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Imports System.IO

Public Class Form1 : Inherits Form

    Friend WithEvents Splitter As New FileSplitter("C:\File.ext") With {.BufferSize = .BufferSize}
    Friend WithEvents Merger As FileSplitter

    ' Splitter settings.
    Private ReadOnly chunkName As String = "File.Part"
    Private ReadOnly chunkExt As String = "fs"

    ' Some default chunk sizes to split a file.
    Private ReadOnly kilobyte As Integer = 1024
    Private ReadOnly megabyte As Integer = 1048576
    Private ReadOnly gigabyte As Integer = 1073741824
    Private ReadOnly halfFileSize As Long = CLng(Me.Splitter.File.Length / 2)

    ' The label controls that will display the progress.
    Friend LabelSplit1 As New Label, LabelSplit2 As New Label, LabelSplit3 As New Label
    Friend LabelMerge1 As New Label, LabelMerge2 As New Label, LabelMerge3 As New Label

    ' The button controls to start a split or merge operation.
    Friend WithEvents ButtonSplit As New Button, ButtonMerge As New Button

    Public Sub New()

        ' This call is required by the designer.
        Me.InitializeComponent()

        ' Set the controls properties.
        With Me.ButtonSplit
            .Text = "Split"
            .Font = New Font(Me.Font.FontFamily, 14.0F, FontStyle.Bold)
            .Size = New Size(200, 75)
            .Location = New Point(0, 0)
            .Cursor = Cursors.Hand
        End With

        With Me.ButtonMerge
            .Text = "Merge"
            .Font = New Font(Me.Font.FontFamily, 14.0F, FontStyle.Bold)
            .Size = New Size(200, 75)
            .Location = New Point(Me.ButtonSplit.Location.X + Me.ButtonSplit.Width, 0)
            .Cursor = Cursors.Hand
        End With

        With Me.LabelSplit1
            .Text = "Total Progress:"
            .AutoSize = True
            .Font = New Font(Me.Font.FontFamily, 9.0F, FontStyle.Regular)
            .Location = New Point(0, Me.ButtonSplit.Location.Y + Me.ButtonSplit.Height + 10)
        End With

        With Me.LabelSplit2
            .Text = "Chunk Progress:"
            .AutoSize = True
            .Font = New Font(Me.Font.FontFamily, 9.0F, FontStyle.Regular)
            .Location = New Point(0, Me.LabelSplit1.Location.Y + Me.LabelSplit1.Height)
        End With

        With Me.LabelSplit3
            .Text = "Chunk Count:"
            .AutoSize = True
            .Font = New Font(Me.Font.FontFamily, 9.0F, FontStyle.Regular)
            .Location = New Point(0, Me.LabelSplit2.Location.Y + Me.LabelSplit2.Height)
        End With

        With Me.LabelMerge1
            .Text = "Total Progress:"
            .AutoSize = True
            .Font = New Font(Me.Font.FontFamily, 9.0F, FontStyle.Regular)
            .Location = New Point(Me.ButtonMerge.Location.X, Me.ButtonMerge.Location.Y + Me.ButtonMerge.Height + 10)
        End With

        With Me.LabelMerge2
            .Text = "Chunk Progress:"
            .AutoSize = True
            .Font = New Font(Me.Font.FontFamily, 9.0F, FontStyle.Regular)
            .Location = New Point(Me.ButtonMerge.Location.X, Me.LabelMerge1.Location.Y + Me.LabelMerge1.Height)
        End With

        With Me.LabelMerge3
            .Text = "Chunk Count:"
            .AutoSize = True
            .Font = New Font(Me.Font.FontFamily, 9.0F, FontStyle.Regular)
            .Location = New Point(Me.ButtonMerge.Location.X, Me.LabelMerge2.Location.Y + Me.LabelMerge2.Height)
        End With

        ' Add the controls on the UI.
        Me.Controls.AddRange({Me.LabelSplit1, Me.LabelSplit2, Me.LabelSplit3,
                              Me.LabelMerge1, Me.LabelMerge2, Me.LabelMerge3,
                              Me.ButtonSplit, Me.ButtonMerge})

        ' Set the Form properties.
        With Me
            .Size = New Size(Me.ButtonSplit.Width + Me.ButtonMerge.Width + 20, 200)
            .FormBorderStyle = FormBorderStyle.FixedDialog
            .MaximizeBox = False
        End With

    End Sub

    Private Sub ButtonSplit_Click() Handles ButtonSplit.Click

        Me.ButtonSplit.Enabled = False

        Me.Splitter.Split(chunkSize:=Me.halfFileSize,
                          chunkName:=Me.chunkName,
                          chunkExt:=Me.chunkExt,
                          overwrite:=True,
                          deleteAfterSplit:=False)

        ' Or...
        'Me.splitter.Split(chunkCount:=2,
        '                  chunkName:=Me.chunkName,
        '                  chunkExt:=Me.chunkExt,
        '                  overwrite:=True,
        '                  deleteAfterSplit:=False)

    End Sub

    ''' <summary>
    ''' Handles the <see cref="Button.Click"/> event of the <see cref="ButtonMerge"/> control.
    ''' </summary>
    Private Sub ButtonMerge_Click() Handles ButtonMerge.Click

        Me.ButtonMerge.Enabled = False

        Me.Merger = New FileSplitter("C:\File.Part.1.fs") With {.BufferSize = .BufferSize}
        Dim targetFileName As String = String.Format("{0}{1}{2}", Me.Merger.File.DirectoryName, "Merged", Me.Merger.File.Extension)

        Me.Merger.Merge(targetFile:=targetFileName,
                        overwrite:=True,
                        deleteChunksAfterMerged:=False)

    End Sub

    ''' <summary>
    ''' Handles the <see cref="FileSplitter.ProgressChanged"/> event of the <see cref="Splitter"/> instance.
    ''' </summary>
    ''' <param name="sender">
    ''' The source of the event.
    ''' </param>
    ''' <param name="e">
    ''' The <see cref="FileSplitterProgressChangedEventArgs"/> instance containing the event data.
    ''' </param>
    Private Sub Splitter_ProgressChanged(ByVal sender As Object, ByVal e As FileSplitterProgressChangedEventArgs) _
    Handles Splitter.ProgressChanged

        Me.LabelSplit1.Text = String.Format("Total Progress: {0}%", e.TotalProgress.ToString("n1"))
        Me.LabelSplit2.Text = String.Format("Chunk Progress: {0}%", e.ChunkProgress.ToString("n1"))
        Me.LabelSplit3.Text = String.Format("Current  Chunk: {0} of {1}", CStr(e.ChunksCreatedOrMerged + 1), CStr(e.ChunksToCreateOrMerge))
        Application.DoEvents()

        If (e.TotalProgress = 100.0R) Then
            Me.ButtonSplit.Enabled = True
        End If

    End Sub

    ''' <summary>
    ''' Handles the <see cref="FileSplitter.ProgressChanged"/> event of the <see cref="Merger"/> instance.
    ''' </summary>
    ''' <param name="sender">
    ''' The source of the event.
    ''' </param>
    ''' <param name="e">
    ''' The <see cref="FileSplitterProgressChangedEventArgs"/> instance containing the event data.
    ''' </param>
    Private Sub Merger_ProgressChanged(ByVal sender As Object, ByVal e As FileSplitterProgressChangedEventArgs) _
    Handles Merger.ProgressChanged

        Me.LabelMerge1.Text = String.Format("Total Progress: {0}%", e.TotalProgress.ToString("n1"))
        Me.LabelMerge2.Text = String.Format("Chunk Progress: {0}%", e.ChunkProgress.ToString("n1"))
        Me.LabelMerge3.Text = String.Format("Current  Chunk: {0} of {1}", CStr(e.ChunksCreatedOrMerged + 1), CStr(e.ChunksToCreateOrMerge))
        Application.DoEvents()

        If (e.TotalProgress = 100.0R) Then
            Me.ButtonMerge.Enabled = True
        End If

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />