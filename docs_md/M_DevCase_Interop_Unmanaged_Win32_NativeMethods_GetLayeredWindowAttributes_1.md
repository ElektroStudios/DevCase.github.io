# NativeMethods.GetLayeredWindowAttributes Method (SafeHandle, UInt32, Int32, LayeredWindowAttributesFlags)
 

Retrieves the opacity and transparency color key of a layered window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool GetLayeredWindowAttributes(
	SafeHandle hWnd,
	ref uint refColorKey,
	ref int refAlpha,
	LayeredWindowAttributesFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetLayeredWindowAttributes ( 
	hWnd As SafeHandle,
	ByRef refColorKey As UInteger,
	ByRef refAlpha As Integer,
	flags As LayeredWindowAttributesFlags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim refColorKey As UInteger
Dim refAlpha As Integer
Dim flags As LayeredWindowAttributesFlags
Dim returnValue As Boolean

returnValue = NativeMethods.GetLayeredWindowAttributes(hWnd, 
	refColorKey, refAlpha, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool GetLayeredWindowAttributes(
	SafeHandle^ hWnd, 
	unsigned int% refColorKey, 
	int% refAlpha, 
	LayeredWindowAttributesFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetLayeredWindowAttributes : 
        hWnd : SafeHandle * 
        refColorKey : uint32 byref * 
        refAlpha : int byref * 
        flags : LayeredWindowAttributesFlags -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the layered window. 

 A layered window is created by specifying <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowStylesEx">Layered</a> when creating the window with the `CreateWindowEx` function or by setting <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowStylesEx">Layered</a> via <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowLongPtr">SetWindowLongPtr(IntPtr, WindowLongValues, IntPtr)</a> function. after the window has been created.</dd><dt>refColorKey</dt><dd>Type: System.UInt32<br />A `COLORREF` structure that receives the transparency color key to be used when composing the layered window. 

 All pixels painted by the window in this color will be transparent. 

 This can be a null reference (`Nothing` in Visual Basic) if the argument is not needed.</dd><dt>refAlpha</dt><dd>Type: System.Int32<br />The Alpha value used to describe the opacity of the layered window. 

 When the variable referred to by *refAlpha* is 0, the window is completely transparent. 

 When the variable referred to by *refAlpha* is 255, the window is opaque. 

 This can be a null reference (`Nothing` in Visual Basic) if the argument is not needed.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_LayeredWindowAttributesFlags">DevCase.Interop.Unmanaged.Win32.Enums.LayeredWindowAttributesFlags</a><br />An action to be taken.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633508%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633508%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetLayeredWindowAttributes">GetLayeredWindowAttributes Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />