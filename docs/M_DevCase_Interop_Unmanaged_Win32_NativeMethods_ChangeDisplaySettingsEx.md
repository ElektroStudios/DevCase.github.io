# NativeMethods.ChangeDisplaySettingsEx Method 
 

Changes the settings of the specified display device to the specified graphics mode.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static DisplaySettingsChange ChangeDisplaySettingsEx(
	string lpszDeviceName,
	ref DevMode refDevMode,
	IntPtr hWnd,
	ChangeDisplaySettingsFlags flags,
	IntPtr lParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Ansi, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function ChangeDisplaySettingsEx ( 
	lpszDeviceName As String,
	ByRef refDevMode As DevMode,
	hWnd As IntPtr,
	flags As ChangeDisplaySettingsFlags,
	lParam As IntPtr
) As DisplaySettingsChange
```

**VB Usage**<br />
``` VB Usage
Dim lpszDeviceName As String
Dim refDevMode As DevMode
Dim hWnd As IntPtr
Dim flags As ChangeDisplaySettingsFlags
Dim lParam As IntPtr
Dim returnValue As DisplaySettingsChange

returnValue = NativeMethods.ChangeDisplaySettingsEx(lpszDeviceName, 
	refDevMode, hWnd, flags, lParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static DisplaySettingsChange ChangeDisplaySettingsEx(
	String^ lpszDeviceName, 
	DevMode% refDevMode, 
	IntPtr hWnd, 
	ChangeDisplaySettingsFlags flags, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member ChangeDisplaySettingsEx : 
        lpszDeviceName : string * 
        refDevMode : DevMode byref * 
        hWnd : IntPtr * 
        flags : ChangeDisplaySettingsFlags * 
        lParam : IntPtr -> DisplaySettingsChange 

```


#### Parameters
&nbsp;<dl><dt>lpszDeviceName</dt><dd>Type: System.String<br />A pointer to a null-terminated string that specifies the display device whose graphics mode will change. 

 Only display device names as returned by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumDisplayDevices">EnumDisplayDevices(String, UInt32, DisplayDevice, UInt32)</a> are valid. The lpszDeviceName parameter can be a null reference (`Nothing` in Visual Basic). A a null reference (`Nothing` in Visual Basic) value specifies the default display device. 

 The default device can be determined by calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumDisplayDevices">EnumDisplayDevices(String, UInt32, DisplayDevice, UInt32)</a> and checking for the `DISPLAY_DEVICE_PRIMARY_DEVICE` flag.</dd><dt>refDevMode</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevCase.Interop.Unmanaged.Win32.Structures.DevMode</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode</a> structure that describes the new graphics mode. 

 If *refDevMode* is a null reference (`Nothing` in Visual Basic), all the values currently in the registry will be used for the display setting. 

 Passing a null reference (`Nothing` in Visual Basic) for the *refDevMode* parameter and 0 for the *flags* parameter is the easiest way to return to the default mode after a dynamic mode change.</dd><dt>hWnd</dt><dd>Type: System.IntPtr<br />Reserved; must be Zero.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ChangeDisplaySettingsFlags">DevCase.Interop.Unmanaged.Win32.Enums.ChangeDisplaySettingsFlags</a><br />Indicates how the graphics mode should be changed.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />If *flags* is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ChangeDisplaySettingsFlags">VideoParameters</a>, *lParam* is a pointer to a `VIDEOPARAMETERS` structure. 

 Otherwise *lParam* must be Zero.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DisplaySettingsChange">DisplaySettingsChange</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DisplaySettingsChange">DisplaySettingsChange</a> value that specifies the operation result.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183413%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183413%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />