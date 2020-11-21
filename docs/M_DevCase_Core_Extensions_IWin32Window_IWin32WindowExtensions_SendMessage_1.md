# IWin32WindowExtensions.SendMessage Method (IWin32Window, Int32, IntPtr, IntPtr)
 

Sends the specified message to the specified window. 

 The SendMessage function calls the window procedure for the specified window and does not return until the window procedure has processed the message.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IWin32Window">DevCase.Core.Extensions.IWin32Window</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IntPtr SendMessage(
	this IWin32Window window,
	int msg,
	IntPtr wParam,
	IntPtr lParam
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function SendMessage ( 
	window As IWin32Window,
	msg As Integer,
	wParam As IntPtr,
	lParam As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim msg As Integer
Dim wParam As IntPtr
Dim lParam As IntPtr
Dim returnValue As IntPtr

returnValue = window.SendMessage(msg, 
	wParam, lParam)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static IntPtr SendMessage(
	IWin32Window^ window, 
	int msg, 
	IntPtr wParam, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member SendMessage : 
        window : IWin32Window * 
        msg : int * 
        wParam : IntPtr * 
        lParam : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The source window.</dd><dt>msg</dt><dd>Type: System.Int32<br />The message to be sent.</dd><dt>wParam</dt><dd>Type: System.IntPtr<br />Additional message-specific information.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />Additional message-specific information.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value specifies the result of the message processing; it depends on the message sent.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IWin32Window. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions">IWin32WindowExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions_SendMessage">SendMessage Overload</a><br /><a href="N_DevCase_Core_Extensions_IWin32Window">DevCase.Core.Extensions.IWin32Window Namespace</a><br />