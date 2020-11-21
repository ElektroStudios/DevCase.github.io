# StreamExtensions.ToArray Method 
 

Writes the Stream content to a Byte array.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Stream">DevCase.Core.Extensions.Stream</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static byte[] ToArray(
	this Stream sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToArray ( 
	sender As Stream
) As Byte()
```

**VB Usage**<br />
``` VB Usage
Dim sender As Stream
Dim returnValue As Byte()

returnValue = sender.ToArray()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static array<unsigned char>^ ToArray(
	Stream^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToArray : 
        sender : Stream -> byte[] 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.Stream<br />The source Stream.</dd></dl>

#### Return Value
Type: Byte[]<br />The resulting Byte array.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Stream. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Stream_StreamExtensions">StreamExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Stream">DevCase.Core.Extensions.Stream Namespace</a><br />