# StringExtensions.SizeInFile Method (String, Encoding)
 

Gets the size, in bytes, of how much a string will occupy when written to a file using the specified Encoding.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int SizeInFile(
	this string sender,
	Encoding enc
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function SizeInFile ( 
	sender As String,
	enc As Encoding
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim enc As Encoding
Dim returnValue As Integer

returnValue = sender.SizeInFile(enc)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static int SizeInFile(
	String^ sender, 
	Encoding^ enc
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SizeInFile : 
        sender : string * 
        enc : Encoding -> int 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>enc</dt><dd>Type: System.Text.Encoding<br />The Encoding.</dd></dl>

#### Return Value
Type: Int32<br />The resulting size, in bytes.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
MsgBox("Test".SizeInFile(Encoding.Default))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_String_StringExtensions_SizeInFile">SizeInFile Overload</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />