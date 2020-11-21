# IWin32WindowExtensions.SendMouseButton Method (IWin32Window, MouseButton)
 

Sends a mouse button click to the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IWin32Window">DevCase.Core.Extensions.IWin32Window</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool SendMouseButton(
	this IWin32Window window,
	MouseButton button
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function SendMouseButton ( 
	window As IWin32Window,
	button As MouseButton
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim button As MouseButton
Dim returnValue As Boolean

returnValue = window.SendMouseButton(button)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static bool SendMouseButton(
	IWin32Window^ window, 
	MouseButton button
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member SendMouseButton : 
        window : IWin32Window * 
        button : MouseButton -> bool 

```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The source window.</dd><dt>button</dt><dd>Type: <a href="T_DevCase_Core_IO_MouseButton">DevCase.Core.IO.MouseButton</a><br />The mouse button to simulate.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the function succeeds; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IWin32Window. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions">IWin32WindowExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions_SendMouseButton">SendMouseButton Overload</a><br /><a href="N_DevCase_Core_Extensions_IWin32Window">DevCase.Core.Extensions.IWin32Window Namespace</a><br />