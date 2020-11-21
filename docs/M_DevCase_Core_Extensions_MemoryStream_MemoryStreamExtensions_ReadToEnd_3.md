# MemoryStreamExtensions.ReadToEnd Method (MemoryStream, Encoding, Int64)
 

Reads all characters from the specified position to the end of the MemoryStream.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_MemoryStream">DevCase.Core.Extensions.MemoryStream</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ReadToEnd(
	this MemoryStream sender,
	Encoding enc,
	long position
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ReadToEnd ( 
	sender As MemoryStream,
	enc As Encoding,
	position As Long
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As MemoryStream
Dim enc As Encoding
Dim position As Long
Dim returnValue As String

returnValue = sender.ReadToEnd(enc, 
	position)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ReadToEnd(
	MemoryStream^ sender, 
	Encoding^ enc, 
	long long position
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ReadToEnd : 
        sender : MemoryStream * 
        enc : Encoding * 
        position : int64 -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.MemoryStream<br />The source MemoryStream.</dd><dt>enc</dt><dd>Type: System.Text.Encoding<br />The encoding.</dd><dt>position</dt><dd>Type: System.Int64<br />The position.</dd></dl>

#### Return Value
Type: String<br />The rest of the stream as a string, from the current position to the end. 

 If the current position is at the end of the stream, returns an empty string ("").

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type MemoryStream. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions">MemoryStreamExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions_ReadToEnd">ReadToEnd Overload</a><br /><a href="N_DevCase_Core_Extensions_MemoryStream">DevCase.Core.Extensions.MemoryStream Namespace</a><br />