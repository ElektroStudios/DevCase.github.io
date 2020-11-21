# NativeMethods.MapVirtualKeyEx Method 
 

Translates (maps) a virtual-key code into a scan code or character value, or translates a scan code into a virtual-key code. 

 The function translates the codes using the input language and an input locale identifier.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CallingConvention = CallingConvention.StdCall, 
	CharSet = CharSet.Unicode, SetLastError = true)]
public static uint MapVirtualKeyEx(
	uint code,
	VirtualKeyMappingTypes mapType,
	IntPtr hkl
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CallingConvention := CallingConvention.StdCall, 
	CharSet := CharSet.Unicode, SetLastError := true>]
Public Shared Function MapVirtualKeyEx ( 
	code As UInteger,
	mapType As VirtualKeyMappingTypes,
	hkl As IntPtr
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim code As UInteger
Dim mapType As VirtualKeyMappingTypes
Dim hkl As IntPtr
Dim returnValue As UInteger

returnValue = NativeMethods.MapVirtualKeyEx(code, 
	mapType, hkl)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CallingConvention = CallingConvention::StdCall, 
	CharSet = CharSet::Unicode, SetLastError = true)]
static unsigned int MapVirtualKeyEx(
	unsigned int code, 
	VirtualKeyMappingTypes mapType, 
	IntPtr hkl
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CallingConvention = CallingConvention.StdCall, 
	CharSet = CharSet.Unicode, SetLastError = true)>]
static member MapVirtualKeyEx : 
        code : uint32 * 
        mapType : VirtualKeyMappingTypes * 
        hkl : IntPtr -> uint32 

```


#### Parameters
&nbsp;<dl><dt>code</dt><dd>Type: System.UInt32<br />The virtual-key code or scan code for a key. 

 How this value is interpreted depends on the value of the *mapType* parameter. 

 The high byte of the *code* value can contain either `0xe0` or `0xe1` to specify the extended scan code.</dd><dt>mapType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_VirtualKeyMappingTypes">DevCase.Interop.Unmanaged.Win32.Enums.VirtualKeyMappingTypes</a><br />The translation to be performed. 

 The value of this parameter depends on the value of the *code* parameter.</dd><dt>hkl</dt><dd>Type: System.IntPtr<br />Input locale identifier to use for translating the specified code. 

 This parameter can be any input locale identifier returned by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetKeyboardLayout">GetKeyboardLayout(UInt32)</a> or `LoadKeyboardLayout` functions.</dd></dl>

#### Return Value
Type: UInt32<br />The return value is either a scan code, a virtual-key code, or a character value, depending on the value of *code* and *mapType* parameters. 

 If there is no translation, the return value is `0`. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646307%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646307%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />