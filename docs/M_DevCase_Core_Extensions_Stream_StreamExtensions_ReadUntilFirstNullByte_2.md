# StreamExtensions.ReadUntilFirstNullByte Method (Stream, Int64, Int64)
 

Reads the bytes of the specified Stream until the first null (zero) byte is found, or until the end, in case of a null byte is not found.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Stream">DevCase.Core.Extensions.Stream</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static byte[] ReadUntilFirstNullByte(
	this Stream sender,
	long startPosition,
	long endPosition
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ReadUntilFirstNullByte ( 
	sender As Stream,
	startPosition As Long,
	endPosition As Long
) As Byte()
```

**VB Usage**<br />
``` VB Usage
Dim sender As Stream
Dim startPosition As Long
Dim endPosition As Long
Dim returnValue As Byte()

returnValue = sender.ReadUntilFirstNullByte(startPosition, 
	endPosition)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static array<unsigned char>^ ReadUntilFirstNullByte(
	Stream^ sender, 
	long long startPosition, 
	long long endPosition
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ReadUntilFirstNullByte : 
        sender : Stream * 
        startPosition : int64 * 
        endPosition : int64 -> byte[] 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.Stream<br />The source Stream to read.</dd><dt>startPosition</dt><dd>Type: System.Int64<br />The position in the source Stream where to start reading bytes.</dd><dt>endPosition</dt><dd>Type: System.Int64<br />The position in the source Stream where to stop reading bytes.</dd></dl>

#### Return Value
Type: Byte[]<br />The bytes read until the first null byte found, or until the end, in case of a null byte is not found.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Stream. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim rawData As Byte() = New Byte() {72, 101, 108, 108, 111, 32, 87, 111, 114, 108, 100, 33, 0, 0, 0} ' "Hello World!\0\0\0"

Using ms As New Global.System.IO.MemoryStream(rawData)
    Dim readable As Byte() = ms.ReadUntilFirstNullByte(startPosition:=ms.Position, endPosition:=ms.Length)
    Dim str As String = Encoding.ASCII.GetString(readable)
    Console.WriteLine(String.Format("""{0}""", str))
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Stream_StreamExtensions">StreamExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Stream_StreamExtensions_ReadUntilFirstNullByte">ReadUntilFirstNullByte Overload</a><br /><a href="N_DevCase_Core_Extensions_Stream">DevCase.Core.Extensions.Stream Namespace</a><br />