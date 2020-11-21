# RadTextBoxControlExtensions.Deserialize Method 
 

Deserializes the text of the RadTextBoxControl from a binary local file. 

 You can use this method to restore the text of a RadTextBoxControl that was saved using the <a href="M_DevCase_ThirdParty_Telerik_Extensions_RadTextBoxControl_RadTextBoxControlExtensions_Serialize">Serialize(RadTextBoxControl, String, SerializationFormat)</a> method.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Telerik_Extensions_RadTextBoxControl">DevCase.ThirdParty.Telerik.Extensions.RadTextBoxControl</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void Deserialize(
	this RadTextBoxControl sender,
	string filepath,
	SerializationFormat format
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub Deserialize ( 
	sender As RadTextBoxControl,
	filepath As String,
	format As SerializationFormat
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As RadTextBoxControl
Dim filepath As String
Dim format As SerializationFormat

sender.Deserialize(filepath, format)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void Deserialize(
	RadTextBoxControl^ sender, 
	String^ filepath, 
	SerializationFormat format
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Deserialize : 
        sender : RadTextBoxControl * 
        filepath : string * 
        format : SerializationFormat -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: RadTextBoxControl<br />The source RadTextBoxControl.</dd><dt>filepath</dt><dd>Type: System.String<br />The source file that contains the serialized items.</dd><dt>format</dt><dd>Type: <a href="T_DevCase_Core_Application_Data_SerializationFormat">DevCase.Core.Application.Data.SerializationFormat</a><br />The serialization format.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RadTextBoxControl. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Telerik_Extensions_RadTextBoxControl_RadTextBoxControlExtensions">RadTextBoxControlExtensions Class</a><br /><a href="N_DevCase_ThirdParty_Telerik_Extensions_RadTextBoxControl">DevCase.ThirdParty.Telerik.Extensions.RadTextBoxControl Namespace</a><br />