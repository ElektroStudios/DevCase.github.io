# NativeMethods.VkKeyScanEx Method 
 

Translates a character to the corresponding virtual-key code and shift state. 

 The function translates the character using the input language and physical keyboard layout identified by the input locale identifier.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static short VkKeyScanEx(
	char character,
	IntPtr hkl = null
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Unicode, SetLastError := true>]
Public Shared Function VkKeyScanEx ( 
	character As Char,
	Optional hkl As IntPtr = Nothing
) As Short
```

**VB Usage**<br />
``` VB Usage
Dim character As Char
Dim hkl As IntPtr
Dim returnValue As Short

returnValue = NativeMethods.VkKeyScanEx(character, 
	hkl)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Unicode, SetLastError = true)]
static short VkKeyScanEx(
	wchar_t character, 
	IntPtr hkl = nullptr
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Unicode, SetLastError = true)>]
static member VkKeyScanEx : 
        character : char * 
        ?hkl : IntPtr 
(* Defaults:
        let _hkl = defaultArg hkl null
*)
-> int16 

```


#### Parameters
&nbsp;<dl><dt>character</dt><dd>Type: System.Char<br />The character to be translated into a virtual-key code.</dd><dt>hkl (Optional)</dt><dd>Type: System.IntPtr<br />Input locale identifier used to translate the character. 

 This parameter can be any input locale identifier previously returned by the `LoadKeyboardLayout` function.</dd></dl>

#### Return Value
Type: Int16<br />If the function succeeds, the low-order byte of the return value contains the virtual-key code, and the high-order byte contains the shift state. 

 If the function finds no key that translates to the passed character code, both the low-order and high-order bytes contain `255`.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/ms646332%28v=VS.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/ms646332%28v=VS.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />