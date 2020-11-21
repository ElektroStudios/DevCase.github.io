# StreamExtensions.ReadUntilFirstNullByte Method (Stream, Int64, Encoding)
 

Reads the bytes of the specified Stream until the first null (zero) byte is found, or until the end, in case of a null byte is not found; and then converts the bytes read to a string representation using the specified text encoding.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Stream">DevCase.Core.Extensions.Stream</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ReadUntilFirstNullByte(
	this Stream sender,
	long startPosition,
	Encoding enc
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ReadUntilFirstNullByte ( 
	sender As Stream,
	startPosition As Long,
	enc As Encoding
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As Stream
Dim startPosition As Long
Dim enc As Encoding
Dim returnValue As String

returnValue = sender.ReadUntilFirstNullByte(startPosition, 
	enc)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ReadUntilFirstNullByte(
	Stream^ sender, 
	long long startPosition, 
	Encoding^ enc
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ReadUntilFirstNullByte : 
        sender : Stream * 
        startPosition : int64 * 
        enc : Encoding -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.Stream<br />The source Stream to read.</dd><dt>startPosition</dt><dd>Type: System.Int64<br />The position in the source Stream where to start reading bytes.</dd><dt>enc</dt><dd>Type: System.Text.Encoding<br />The text encoding used to represent the bytes read.</dd></dl>

#### Return Value
Type: String<br />The resulting string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Stream. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim rawData As Byte() = New Byte() {72, 101, 108, 108, 111, 32, 87, 111, 114, 108, 100, 33, 0, 0, 0} ' "Hello World!\0\0\0"

Using ms As New Global.System.IO.MemoryStream(rawData)
    Dim str As String = ms.ReadUntilFirstNullByte(startPosition:=ms.Position, enc:=Encoding.ASCII)
    Console.WriteLine(String.Format("""{0}""", str))
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Stream_StreamExtensions">StreamExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Stream_StreamExtensions_ReadUntilFirstNullByte">ReadUntilFirstNullByte Overload</a><br /><a href="N_DevCase_Core_Extensions_Stream">DevCase.Core.Extensions.Stream Namespace</a><br />