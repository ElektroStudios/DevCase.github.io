# IWin32WindowExtensions.PostMessage Method (IWin32Window, Int32, IntPtr, IntPtr)
 

Places (posts) a message in the message queue associated with the thread that created the specified window, and returns without waiting for the thread to process the message.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IWin32Window">DevCase.Core.Extensions.IWin32Window</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool PostMessage(
	this IWin32Window window,
	int msg,
	IntPtr wParam,
	IntPtr lParam
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function PostMessage ( 
	window As IWin32Window,
	msg As Integer,
	wParam As IntPtr,
	lParam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim msg As Integer
Dim wParam As IntPtr
Dim lParam As IntPtr
Dim returnValue As Boolean

returnValue = window.PostMessage(msg, 
	wParam, lParam)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static bool PostMessage(
	IWin32Window^ window, 
	int msg, 
	IntPtr wParam, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member PostMessage : 
        window : IWin32Window * 
        msg : int * 
        wParam : IntPtr * 
        lParam : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The source window.</dd><dt>msg</dt><dd>Type: System.Int32<br />The message to be sent.</dd><dt>wParam</dt><dd>Type: System.IntPtr<br />\[Missing <param name="wParam"/> documentation for "M:DevCase.Core.Extensions.IWin32Window.IWin32WindowExtensions.PostMessage(System.Windows.Forms.IWin32Window,System.Int32,System.IntPtr,System.IntPtr)"\]</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />\[Missing <param name="lParam"/> documentation for "M:DevCase.Core.Extensions.IWin32Window.IWin32WindowExtensions.PostMessage(System.Windows.Forms.IWin32Window,System.Int32,System.IntPtr,System.IntPtr)"\]</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IWin32Window. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions">IWin32WindowExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions_PostMessage">PostMessage Overload</a><br /><a href="N_DevCase_Core_Extensions_IWin32Window">DevCase.Core.Extensions.IWin32Window Namespace</a><br />