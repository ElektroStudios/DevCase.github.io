# ScreenExtensions.CreateDeviceContext Method 
 

Creates a device context (DC) for the source Screen and returns a IntPtr pointing to the created device context. 

 The device context is an opaque data structure, whose values are used internally by GDI. You can use the returned IntPtr in subsequent GDI functions to draw in the device context. 

 The device context must be released by calling the the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ReleaseDC">ReleaseDC(IntPtr, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Screen">DevCase.Core.Extensions.Screen</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IntPtr CreateDeviceContext(
	this Screen sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function CreateDeviceContext ( 
	sender As Screen
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim sender As Screen
Dim returnValue As IntPtr

returnValue = sender.CreateDeviceContext()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IntPtr CreateDeviceContext(
	Screen^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CreateDeviceContext : 
        sender : Screen -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.Screen<br />The source Screen.</dd></dl>

#### Return Value
Type: IntPtr<br />A IntPtr pointing to the created device context.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Screen. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim scr As Screen = Screen.PrimaryScreen
Dim hdc As IntPtr = scr.CreateDeviceContext()

' Release the device context.
NativeMethods.ReleaseDC(IntPtr.Zero, hdc)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Screen_ScreenExtensions">ScreenExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Screen">DevCase.Core.Extensions.Screen Namespace</a><br />