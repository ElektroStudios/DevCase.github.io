# StreamExtensions.SeekToBegin Method 
 

Sets the position to the beginning of the source stream.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Stream">DevCase.Core.Extensions.Stream</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static long SeekToBegin(
	this ref Stream sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function SeekToBegin ( 
	ByRef sender As Stream
) As Long
```

**VB Usage**<br />
``` VB Usage
Dim sender As Stream
Dim returnValue As Long

returnValue = sender.SeekToBegin()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static long long SeekToBegin(
	Stream^% sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SeekToBegin : 
        sender : Stream byref -> int64 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.Stream<br />The source Stream.</dd></dl>

#### Return Value
Type: Int64<br />The new position within the source stream.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Stream_StreamExtensions">StreamExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Stream">DevCase.Core.Extensions.Stream Namespace</a><br />