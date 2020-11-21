# IWin32WindowExtensions.SendKeyAsync Method (IWin32Window, Keys, KeyBehavior)
 

Asynchronouslly sends a keystroke to the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IWin32Window">DevCase.Core.Extensions.IWin32Window</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool SendKeyAsync(
	this IWin32Window window,
	Keys key,
	KeyBehavior behavior
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function SendKeyAsync ( 
	window As IWin32Window,
	key As Keys,
	behavior As KeyBehavior
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim key As Keys
Dim behavior As KeyBehavior
Dim returnValue As Boolean

returnValue = window.SendKeyAsync(key, 
	behavior)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static bool SendKeyAsync(
	IWin32Window^ window, 
	Keys key, 
	KeyBehavior behavior
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member SendKeyAsync : 
        window : IWin32Window * 
        key : Keys * 
        behavior : KeyBehavior -> bool 

```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The source window.</dd><dt>key</dt><dd>Type: System.Windows.Forms.Keys<br />The key to synthesize.</dd><dt>behavior</dt><dd>Type: <a href="T_DevCase_Core_IO_KeyBehavior">DevCase.Core.IO.KeyBehavior</a><br />The keystroke behavior.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IWin32Window. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions">IWin32WindowExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions_SendKeyAsync">SendKeyAsync Overload</a><br /><a href="N_DevCase_Core_Extensions_IWin32Window">DevCase.Core.Extensions.IWin32Window Namespace</a><br />