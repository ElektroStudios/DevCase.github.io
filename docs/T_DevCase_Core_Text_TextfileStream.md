# TextfileStream Class
 

Reads and manages the contents of a textfile. It encapsulates an underliying <a href="P_DevCase_Core_Text_TextfileStream_FileStream">FileStream</a> to access the file.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Text.TextfileStream<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class TextfileStream : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public Class TextfileStream
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As TextfileStream
```

**C++**<br />
``` C++
public ref class TextfileStream : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
type TextfileStream =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The TextfileStream type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_TextfileStream__ctor">TextfileStream</a></td><td>
Initializes a new instance of the TextfileStream class.</td></tr></table>&nbsp;
<a href="#textfilestream-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_TextfileStream_Encoding">Encoding</a></td><td>
Gets the textfile <a href="P_DevCase_Core_Text_TextfileStream_Encoding">Encoding</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_TextfileStream_FileHandle">FileHandle</a></td><td>
Gets a SafeFileHandle object that represents the operating system file handle of the textfile.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_TextfileStream_Filepath">Filepath</a></td><td>
Gets the textfile path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_TextfileStream_FileStream">FileStream</a></td><td>
Gets the <a href="P_DevCase_Core_Text_TextfileStream_FileStream">FileStream</a> instance that exposes a Stream around the textfile.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_TextfileStream_Lines">Lines</a></td><td>
Gets or sets the textfile lines.</td></tr></table>&nbsp;
<a href="#textfilestream-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_TextfileStream_Close">Close</a></td><td>
Closes the current stream and releases any resources (such as sockets and file handles) associated with the current stream.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_TextfileStream_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_TextfileStream_Lock">Lock</a></td><td>
Prevents other processes from reading or writing to the textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_TextfileStream_Save_1">Save(Encoding)</a></td><td>
Save the lines of the current textfile, in the current textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_TextfileStream_Save">Save(String, Encoding)</a></td><td>
Save the lines of the current textfile, in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_TextfileStream_ToString">ToString</a></td><td>
Returns a String that represents this instance.
 (Overrides AestheticObject.ToString().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_TextfileStream_Unlock">Unlock</a></td><td>
Allows access by other processes to read or write to a textfile that was previously locked.</td></tr></table>&nbsp;
<a href="#textfilestream-class">Back to Top</a>

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
<a href="#textfilestream-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using txtFile As New TextfileStream("C:\File.txt", Encoding.Default)

    With txtFile
        .Lock()
        .Lines.Add("Test")
        .Lines(0) = "Hello World!"
        .Save()
        .Unlock()
    End With

    Dim lineIndex As Integer
    Dim lineCount As Integer = txtFile.Lines.Count
    Dim textFormat As String =
        String.Join(ControlChars.NewLine,
                    From line As String In txtFile.Lines
                    Select String.Format("{0}: {1}",
                    Interlocked.Increment(lineIndex).ToString(New String("0"c, lineCount.ToString().Length)), line))

    Console.WriteLine(String.Format("FilePath: {0}", txtFile.Filepath))
    Console.WriteLine(String.Format("Encoding: {0}", txtFile.Encoding.WebName))
    Console.WriteLine(String.Format("Lines   : {0}", Environment.NewLine + textFormat))

End Using
```


## See Also


#### Reference
<a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />