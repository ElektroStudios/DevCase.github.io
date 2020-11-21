# TexfileLines Class
 

Defines a List(T) that contains the text-lines of a textfile.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Collections.Generic.List(String)<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticList_1">DevCase.Core.Design.AestheticList</a>(String)<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Text.TexfileLines<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("TexfileLines")]
public class TexfileLines : AestheticList<string>
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("TexfileLines")>
Public Class TexfileLines
	Inherits AestheticList(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim instance As TexfileLines
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"TexfileLines")]
public ref class TexfileLines : public AestheticList<String^>
```

**F#**<br />
``` F#
[<SerializableAttribute>]
[<XmlRootAttribute("TexfileLines")>]
type TexfileLines =  
    class
        inherit AestheticList<string>
    end
```

The TexfileLines type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_TexfileLines__ctor">TexfileLines(IEnumerable(String))</a></td><td>
Initializes a new instance of the TexfileLines class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_TexfileLines__ctor_1">TexfileLines(String)</a></td><td>
Prevents a default instance of the TexfileLines class from being created.</td></tr></table>&nbsp;
<a href="#texfilelines-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_TexfileLines_CountBlank">CountBlank</a></td><td>
Gets the number of blank elements actually contained in the List(T).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_TexfileLines_CountNonBlank">CountNonBlank</a></td><td>
Gets the number of non-blank elements actually contained in the List(T).</td></tr></table>&nbsp;
<a href="#texfilelines-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_TexfileLines_Randomize">Randomize</a></td><td>
Randomizes the elements of this TexfileLines.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_TexfileLines_RemoveAt">RemoveAt</a></td><td>
Removes the elements at the specified indices of this TexfileLines.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_TexfileLines_Trim">Trim</a></td><td>
Removes all leading and trailing occurrences of a set of characters from all the elements of this TexfileLines.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_TexfileLines_TrimEnd">TrimEnd</a></td><td>
Removes all trailing occurrences of a set of characters from all the elements of this TexfileLines.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_TexfileLines_TrimStart">TrimStart</a></td><td>
Removes all leading occurrences of a set of characters from all the elements of this TexfileLines.</td></tr></table>&nbsp;
<a href="#texfilelines-class">Back to Top</a>

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
<a href="#texfilelines-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using txtFile As New TextfileStream("C:\file.txt", Encoding.Default)

    Dim txtLines As TexfileLines = txtFile.Lines

    txtLines.Add("  Hello World!  ")
    txtLines.Trim(" "c)
    txtLines.Randomize()

    Dim lineIndex As Integer
    Dim lineCount As Integer = txtFile.Lines.Count
    Dim textFormat As String =
        String.Join(ControlChars.NewLine,
                    From line As String In txtFile.Lines
                    Select String.Format("{0}: {1}",
                           Interlocked.Increment(lineIndex).ToString(New String("0"c, lineCount.ToString().Length)), line))

    Console.WriteLine(String.Format("Filepath.......: {0}", txtFile.Filepath))
    Console.WriteLine(String.Format("Blank lines....: {0}", txtLines.CountBlank))
    Console.WriteLine(String.Format("Non-blank lines: {0}", txtLines.CountNonBlank))
    Console.WriteLine(String.Format("Lines..........: {0}", Environment.NewLine + textFormat))

End Using
```


## See Also


#### Reference
<a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />