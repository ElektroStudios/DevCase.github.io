# NativeMethods.LoadKeyboardLayout Method 
 

Loads a new input locale identifier (formerly called the keyboard layout) into the system.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr LoadKeyboardLayout(
	string klid,
	KeyboardLayoutFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function LoadKeyboardLayout ( 
	klid As String,
	flags As KeyboardLayoutFlags
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim klid As String
Dim flags As KeyboardLayoutFlags
Dim returnValue As IntPtr

returnValue = NativeMethods.LoadKeyboardLayout(klid, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr LoadKeyboardLayout(
	String^ klid, 
	KeyboardLayoutFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member LoadKeyboardLayout : 
        klid : string * 
        flags : KeyboardLayoutFlags -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>klid</dt><dd>Type: System.String<br />The name of the input locale identifier to load. 

 This name is a string composed of the hexadecimal value of the Language Identifier (low word) and a device identifier (high word). 

 For example, U.S. English has a language identifier of 0x0409, so the primary U.S. English layout is named "00000409". 

 Variants of U.S. English layout (such as the Dvorak layout) are named "00010409", "00020409", and so on.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_KeyboardLayoutFlags">DevCase.Interop.Unmanaged.Win32.Enums.KeyboardLayoutFlags</a><br />Specifies how the input locale identifier is to be loaded</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the input locale identifier corresponding to the name specified in *klid*. 

 If no matching locale is available, the return value is the default language of the system.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-loadkeyboardlayouta" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-loadkeyboardlayouta</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />