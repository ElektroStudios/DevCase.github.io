# ByteExtensions.ReadUntilFirstNullByte Method (Byte[], Int32, Encoding)
 

Reads the specified bytes until the first null (zero) byte is found, or until the end, in case of a null byte is not found; and then converts the bytes read to a string representation using the specified text encoding.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Byte">DevCase.Core.Extensions.Byte</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ReadUntilFirstNullByte(
	this byte[] sender,
	int startIndex,
	Encoding enc
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ReadUntilFirstNullByte ( 
	sender As Byte(),
	startIndex As Integer,
	enc As Encoding
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As Byte()
Dim startIndex As Integer
Dim enc As Encoding
Dim returnValue As String

returnValue = sender.ReadUntilFirstNullByte(startIndex, 
	enc)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ReadUntilFirstNullByte(
	array<unsigned char>^ sender, 
	int startIndex, 
	Encoding^ enc
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ReadUntilFirstNullByte : 
        sender : byte[] * 
        startIndex : int * 
        enc : Encoding -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Byte[]<br />The byte data to read.</dd><dt>startIndex</dt><dd>Type: System.Int32<br />The position in the byte array where to start reading bytes.</dd><dt>enc</dt><dd>Type: System.Text.Encoding<br />The text encoding used to represent the bytes read.</dd></dl>

#### Return Value
Type: String<br />The resulting string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim rawData As Byte() = New Byte() {72, 101, 108, 108, 111, 32, 87, 111, 114, 108, 100, 33, 0, 0, 0} ' "Hello World!\0\0\0"
Dim str As String = ReadUntilFirstNullByte(rawData, startIndex:=0, enc:=Encoding.ASCII)
MsgBox(String.Format("""{0}""", str))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Byte_ByteExtensions">ByteExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Byte_ByteExtensions_ReadUntilFirstNullByte">ReadUntilFirstNullByte Overload</a><br /><a href="N_DevCase_Core_Extensions_Byte">DevCase.Core.Extensions.Byte Namespace</a><br />