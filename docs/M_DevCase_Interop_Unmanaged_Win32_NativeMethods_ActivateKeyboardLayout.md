# NativeMethods.ActivateKeyboardLayout Method 
 

Sets the input locale identifier (formerly called the keyboard layout handle) for the calling thread or the current process. 

 The input locale identifier specifies a locale as well as the physical layout of the keyboard.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static IntPtr ActivateKeyboardLayout(
	IntPtr hkl,
	KeyboardLayoutFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ActivateKeyboardLayout ( 
	hkl As IntPtr,
	flags As KeyboardLayoutFlags
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hkl As IntPtr
Dim flags As KeyboardLayoutFlags
Dim returnValue As IntPtr

returnValue = NativeMethods.ActivateKeyboardLayout(hkl, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static IntPtr ActivateKeyboardLayout(
	IntPtr hkl, 
	KeyboardLayoutFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member ActivateKeyboardLayout : 
        hkl : IntPtr * 
        flags : KeyboardLayoutFlags -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hkl</dt><dd>Type: System.IntPtr<br />Input locale identifier to be activated. 

 The input locale identifier must have been loaded by a previous call to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadKeyboardLayout">LoadKeyboardLayout(String, KeyboardLayoutFlags)</a> function.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_KeyboardLayoutFlags">DevCase.Interop.Unmanaged.Win32.Enums.KeyboardLayoutFlags</a><br />Specifies how the input locale identifier is to be activated</dd></dl>

#### Return Value
Type: IntPtr<br />The return value is of type HKL. 

 If the function succeeds, the return value is the previous input locale identifier. Otherwise, it is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-activatekeyboardlayout" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-activatekeyboardlayout</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />