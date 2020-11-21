# ByteExtensions.ToString Method (IEnumerable(Byte), Encoding)
 

Converts a byte sequence to its String representation using the specified character Encoding.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Byte">DevCase.Core.Extensions.Byte</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ToString(
	this IEnumerable<byte> sender,
	Encoding enc
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToString ( 
	sender As IEnumerable(Of Byte),
	enc As Encoding
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of Byte)
Dim enc As Encoding
Dim returnValue As String

returnValue = sender.ToString(enc)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ToString(
	IEnumerable<unsigned char>^ sender, 
	Encoding^ enc
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToString : 
        sender : IEnumerable<byte> * 
        enc : Encoding -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(Byte)<br />The source <a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array</a>.</dd><dt>enc</dt><dd>Type: System.Text.Encoding<br />The character Encoding to decode the bytes.</dd></dl>

#### Return Value
Type: String<br />The String representation.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(Byte). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
MessageBox.Show(New Byte() {84, 101, 115, 116}.ToString(Encoding.Default))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Byte_ByteExtensions">ByteExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Byte_ByteExtensions_ToString">ToString Overload</a><br /><a href="N_DevCase_Core_Extensions_Byte">DevCase.Core.Extensions.Byte Namespace</a><br />