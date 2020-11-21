# NativeMethods.EnumDisplaySettings Method 
 

Retrieves information about one of the graphics modes for a display device. 

 To retrieve information for all the graphics modes of a display device, make a series of calls to this function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool EnumDisplaySettings(
	string deviceName,
	EnumDisplaySettingsMode modeNum,
	ref DevMode refDevMode
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Ansi, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function EnumDisplaySettings ( 
	deviceName As String,
	modeNum As EnumDisplaySettingsMode,
	ByRef refDevMode As DevMode
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim deviceName As String
Dim modeNum As EnumDisplaySettingsMode
Dim refDevMode As DevMode
Dim returnValue As Boolean

returnValue = NativeMethods.EnumDisplaySettings(deviceName, 
	modeNum, refDevMode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool EnumDisplaySettings(
	String^ deviceName, 
	EnumDisplaySettingsMode modeNum, 
	DevMode% refDevMode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member EnumDisplaySettings : 
        deviceName : string * 
        modeNum : EnumDisplaySettingsMode * 
        refDevMode : DevMode byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>deviceName</dt><dd>Type: System.String<br />A pointer to a null-terminated string that specifies the display device about whose graphics mode the function will obtain information. 

 This parameter is either a null reference (`Nothing` in Visual Basic) or a `DISPLAY_DEVICE.DeviceName` returned from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumDisplayDevices">EnumDisplayDevices(String, UInt32, DisplayDevice, UInt32)</a>. 

 A a null reference (`Nothing` in Visual Basic) value specifies the current display device on the computer on which the calling thread is running.</dd><dt>modeNum</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EnumDisplaySettingsMode">DevCase.Interop.Unmanaged.Win32.Enums.EnumDisplaySettingsMode</a><br />The type of information to be retrieved. 

 Graphics mode indices start at zero. 

 To obtain information for all of a display device's graphics modes, make a series of calls to EnumDisplaySettings(String, EnumDisplaySettingsMode, DevMode), as follows: 

 Set `iModeNum` to zero for the first call, and increment `iModeNum` by one for each subsequent call. Continue calling the function until the return value is zero.</dd><dt>refDevMode</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevCase.Interop.Unmanaged.Win32.Structures.DevMode</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode</a> structure into which the function stores information about the specified graphics mode. 

 Before calling EnumDisplaySettings(String, EnumDisplaySettingsMode, DevMode), set the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_SizeOfStruct">SizeOfStruct</a> member to `Marshal.SizeOf(Of DevMode)`, and set the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_DriverExtra">DriverExtra</a> member to indicate the size, in bytes, of the additional space available to receive private driver data.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd162611%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd162611%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />