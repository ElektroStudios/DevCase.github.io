# NativeMethods.UnloadKeyboardLayout Method 
 

Unloads an input locale identifier (formerly called a keyboard layout).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static bool UnloadKeyboardLayout(
	IntPtr hkl
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function UnloadKeyboardLayout ( 
	hkl As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hkl As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.UnloadKeyboardLayout(hkl)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static bool UnloadKeyboardLayout(
	IntPtr hkl
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member UnloadKeyboardLayout : 
        hkl : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hkl</dt><dd>Type: System.IntPtr<br />The input locale identifier to be unloaded.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-unloadkeyboardlayout" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-unloadkeyboardlayout</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />