# NativeMethods.ChangeDisplaySettings Method 
 

Changes the settings of the default display device to the specified graphics mode.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static DisplaySettingsChange ChangeDisplaySettings(
	ref DevMode refDevMode,
	ChangeDisplaySettingsFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Ansi, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function ChangeDisplaySettings ( 
	ByRef refDevMode As DevMode,
	flags As ChangeDisplaySettingsFlags
) As DisplaySettingsChange
```

**VB Usage**<br />
``` VB Usage
Dim refDevMode As DevMode
Dim flags As ChangeDisplaySettingsFlags
Dim returnValue As DisplaySettingsChange

returnValue = NativeMethods.ChangeDisplaySettings(refDevMode, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static DisplaySettingsChange ChangeDisplaySettings(
	DevMode% refDevMode, 
	ChangeDisplaySettingsFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member ChangeDisplaySettings : 
        refDevMode : DevMode byref * 
        flags : ChangeDisplaySettingsFlags -> DisplaySettingsChange 

```


#### Parameters
&nbsp;<dl><dt>refDevMode</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevCase.Interop.Unmanaged.Win32.Structures.DevMode</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode</a> structure that describes the new graphics mode. 

 If *refDevMode* is a null reference (`Nothing` in Visual Basic), all the values currently in the registry will be used for the display setting. 

 Passing a null reference (`Nothing` in Visual Basic) for the *refDevMode* parameter and 0 for the *flags* parameter is the easiest way to return to the default mode after a dynamic mode change.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ChangeDisplaySettingsFlags">DevCase.Interop.Unmanaged.Win32.Enums.ChangeDisplaySettingsFlags</a><br />Indicates how the graphics mode should be changed.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DisplaySettingsChange">DisplaySettingsChange</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DisplaySettingsChange">DisplaySettingsChange</a> value that specifies the operation result.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183411%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183411%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />