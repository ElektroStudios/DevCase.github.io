# IWin32WindowExtensions.ResumeDrawing Method (IWin32Window, Boolean)
 

Allow the specified window to be redrawn. 

 By calling this method, it will allow painting events to be fired on the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IWin32Window">DevCase.Core.Extensions.IWin32Window</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void ResumeDrawing(
	this IWin32Window sender,
	bool redraw
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub ResumeDrawing ( 
	sender As IWin32Window,
	redraw As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As IWin32Window
Dim redraw As Boolean

sender.ResumeDrawing(redraw)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void ResumeDrawing(
	IWin32Window^ sender, 
	bool redraw
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ResumeDrawing : 
        sender : IWin32Window * 
        redraw : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The source IWin32Window.</dd><dt>redraw</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), causes the window to de redrawn.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IWin32Window. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions">IWin32WindowExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions_ResumeDrawing">ResumeDrawing Overload</a><br /><a href="N_DevCase_Core_Extensions_IWin32Window">DevCase.Core.Extensions.IWin32Window Namespace</a><br />