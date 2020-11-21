# NativeMethods.CallNextHookEx Method (IntPtr, Int32, IntPtr, MouseLowLevelHookStruct)
 

Passes the hook information to the next hook procedure in the current hook chain. 

 A hook procedure can call this function either before or after processing the hook information.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static IntPtr CallNextHookEx(
	IntPtr hhk,
	int nCode,
	IntPtr wParam,
	in MouseLowLevelHookStruct refLParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function CallNextHookEx ( 
	hhk As IntPtr,
	nCode As Integer,
	wParam As IntPtr,
	ByRef refLParam As MouseLowLevelHookStruct
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hhk As IntPtr
Dim nCode As Integer
Dim wParam As IntPtr
Dim refLParam As MouseLowLevelHookStruct
Dim returnValue As IntPtr

returnValue = NativeMethods.CallNextHookEx(hhk, 
	nCode, wParam, refLParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static IntPtr CallNextHookEx(
	IntPtr hhk, 
	int nCode, 
	IntPtr wParam, 
	[InAttribute] MouseLowLevelHookStruct% refLParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member CallNextHookEx : 
        hhk : IntPtr * 
        nCode : int * 
        wParam : IntPtr * 
        refLParam : MouseLowLevelHookStruct byref -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hhk</dt><dd>Type: System.IntPtr<br />This parameter is ignored.</dd><dt>nCode</dt><dd>Type: System.Int32<br />The hook code passed to the current hook procedure. 

 The next hook procedure uses this code to determine how to process the hook information.</dd><dt>wParam</dt><dd>Type: System.IntPtr<br />The wParam value passed to the current hook procedure. 

 The meaning of this parameter depends on the type of hook associated with the current hook chain.</dd><dt>refLParam</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MouseLowLevelHookStruct">DevCase.Interop.Unmanaged.Win32.Structures.MouseLowLevelHookStruct</a><br />The lParam value passed to the current hook procedure. 

 The meaning of this parameter depends on the type of hook associated with the current hook chain.</dd></dl>

#### Return Value
Type: IntPtr<br />This value is returned by the next hook procedure in the chain. 

 The current hook procedure must also return this value. 

 The meaning of the return value depends on the hook type. 

 For more information, see the descriptions of the individual hook procedures.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms644974%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms644974%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CallNextHookEx">CallNextHookEx Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />