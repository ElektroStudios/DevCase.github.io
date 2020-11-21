# NativeMethods.VkKeyScan Method 
 

**Note: This API is now obsolete.**

Translates a character to the corresponding virtual-key code and shift state for the current keyboard.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
[ObsoleteAttribute]
public static short VkKeyScan(
	char character
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
<ObsoleteAttribute>
Public Shared Function VkKeyScan ( 
	character As Char
) As Short
```

**VB Usage**<br />
``` VB Usage
Dim character As Char
Dim returnValue As Short

returnValue = NativeMethods.VkKeyScan(character)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
[ObsoleteAttribute]
static short VkKeyScan(
	wchar_t character
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
[<ObsoleteAttribute>]
static member VkKeyScan : 
        character : char -> int16 

```


#### Parameters
&nbsp;<dl><dt>character</dt><dd>Type: System.Char<br />The character to be translated into a virtual-key code.</dd></dl>

#### Return Value
Type: Int16<br />If the function succeeds, the low-order byte of the return value contains the virtual-key code, and the high-order byte contains the shift state. 

 If the function finds no key that translates to the passed character code, both the low-order and high-order bytes contain `–1`.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646329%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646329%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />