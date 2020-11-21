# ThreadExtensions.PostThreadMessage Method (Thread, WindowMessages, IntPtr, IntPtr)
 

Places (posts) a message to the message queue of the specified thread. 

 It returns without waiting for the thread to process the message.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Thread">DevCase.Core.Extensions.Thread</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool PostThreadMessage(
	this Thread tr,
	WindowMessages msg,
	IntPtr wParam,
	IntPtr lParam
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function PostThreadMessage ( 
	tr As Thread,
	msg As WindowMessages,
	wParam As IntPtr,
	lParam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim tr As Thread
Dim msg As WindowMessages
Dim wParam As IntPtr
Dim lParam As IntPtr
Dim returnValue As Boolean

returnValue = tr.PostThreadMessage(msg, 
	wParam, lParam)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static bool PostThreadMessage(
	Thread^ tr, 
	WindowMessages msg, 
	IntPtr wParam, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member PostThreadMessage : 
        tr : Thread * 
        msg : WindowMessages * 
        wParam : IntPtr * 
        lParam : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>tr</dt><dd>Type: System.Threading.Thread<br />The source Thread.</dd><dt>msg</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages</a><br />The type of message to be posted.</dd><dt>wParam</dt><dd>Type: System.IntPtr<br />\[Missing <param name="wParam"/> documentation for "M:DevCase.Core.Extensions.Thread.ThreadExtensions.PostThreadMessage(System.Threading.Thread,DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages,System.IntPtr,System.IntPtr)"\]</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />\[Missing <param name="lParam"/> documentation for "M:DevCase.Core.Extensions.Thread.ThreadExtensions.PostThreadMessage(System.Threading.Thread,DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages,System.IntPtr,System.IntPtr)"\]</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Thread. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Thread_ThreadExtensions">ThreadExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Thread_ThreadExtensions_PostThreadMessage">PostThreadMessage Overload</a><br /><a href="N_DevCase_Core_Extensions_Thread">DevCase.Core.Extensions.Thread Namespace</a><br />