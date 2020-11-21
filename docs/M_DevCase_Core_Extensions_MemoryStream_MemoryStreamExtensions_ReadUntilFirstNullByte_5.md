# MemoryStreamExtensions.ReadUntilFirstNullByte Method (MemoryStream, Encoding)
 

Reads the bytes of the specified MemoryStream until the first null (zero) byte is found, or until the end, in case of a null byte is not found; and then converts the bytes read to a string representation using the specified text encoding.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_MemoryStream">DevCase.Core.Extensions.MemoryStream</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ReadUntilFirstNullByte(
	this MemoryStream sender,
	Encoding enc
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ReadUntilFirstNullByte ( 
	sender As MemoryStream,
	enc As Encoding
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As MemoryStream
Dim enc As Encoding
Dim returnValue As String

returnValue = sender.ReadUntilFirstNullByte(enc)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ReadUntilFirstNullByte(
	MemoryStream^ sender, 
	Encoding^ enc
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ReadUntilFirstNullByte : 
        sender : MemoryStream * 
        enc : Encoding -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.MemoryStream<br />The source MemoryStream to read.</dd><dt>enc</dt><dd>Type: System.Text.Encoding<br />The text encoding used to represent the bytes read.</dd></dl>

#### Return Value
Type: String<br />The resulting string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type MemoryStream. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim rawData As Byte() = New Byte() {72, 101, 108, 108, 111, 32, 87, 111, 114, 108, 100, 33, 0, 0, 0} ' "Hello World!\0\0\0"

Using ms As New Global.System.IO.MemoryStream(rawData)
    Dim readable As Byte() = ms.ReadUntilFirstNullByte(Encoding.ASCII)
    Dim str As String = Encoding.ASCII.GetString(readable)
    Console.WriteLine(String.Format("""{0}""", str))
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions">MemoryStreamExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions_ReadUntilFirstNullByte">ReadUntilFirstNullByte Overload</a><br /><a href="N_DevCase_Core_Extensions_MemoryStream">DevCase.Core.Extensions.MemoryStream Namespace</a><br />