# NativeMethods.MapVirtualKey Method 
 

Translates (maps) a virtual-key code into a scan code or character value, or translates a scan code into a virtual-key code. 

 To specify a handle to the keyboard layout to use for translating the specified code, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MapVirtualKeyEx">MapVirtualKeyEx(UInt32, VirtualKeyMappingTypes, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CallingConvention = CallingConvention.StdCall, 
	CharSet = CharSet.Unicode, SetLastError = true)]
public static uint MapVirtualKey(
	uint code,
	VirtualKeyMappingTypes mapType
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CallingConvention := CallingConvention.StdCall, 
	CharSet := CharSet.Unicode, SetLastError := true>]
Public Shared Function MapVirtualKey ( 
	code As UInteger,
	mapType As VirtualKeyMappingTypes
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim code As UInteger
Dim mapType As VirtualKeyMappingTypes
Dim returnValue As UInteger

returnValue = NativeMethods.MapVirtualKey(code, 
	mapType)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CallingConvention = CallingConvention::StdCall, 
	CharSet = CharSet::Unicode, SetLastError = true)]
static unsigned int MapVirtualKey(
	unsigned int code, 
	VirtualKeyMappingTypes mapType
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CallingConvention = CallingConvention.StdCall, 
	CharSet = CharSet.Unicode, SetLastError = true)>]
static member MapVirtualKey : 
        code : uint32 * 
        mapType : VirtualKeyMappingTypes -> uint32 

```


#### Parameters
&nbsp;<dl><dt>code</dt><dd>Type: System.UInt32<br />The virtual-key code or scan code for a key. 

 How this value is interpreted depends on the value of the *mapType* parameter.</dd><dt>mapType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_VirtualKeyMappingTypes">DevCase.Interop.Unmanaged.Win32.Enums.VirtualKeyMappingTypes</a><br />The translation to be performed. 

 The value of this parameter depends on the value of the *code* parameter.</dd></dl>

#### Return Value
Type: UInt32<br />The return value is either a scan code, a virtual-key code, or a character value, depending on the value of *code* and *mapType* parameters. 

 If there is no translation, the return value is `0`. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646306%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646306%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />