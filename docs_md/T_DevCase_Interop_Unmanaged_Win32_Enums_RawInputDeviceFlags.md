# RawInputDeviceFlags Enumeration
 

Flags combinations for of <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice_Flags">Flags</a> member.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum RawInputDeviceFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration RawInputDeviceFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As RawInputDeviceFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class RawInputDeviceFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type RawInputDeviceFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawInputDeviceFlags.AppKeys">**AppKeys**</td><td>1024</td><td>If set, the application command keys are handled. 

AppKeys can be specified only if NoLegacy is specified for a keyboard device.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawInputDeviceFlags.CaptureMouse">**CaptureMouse**</td><td>512</td><td>If set, the mouse button click does not activate the other window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawInputDeviceFlags.DevNotify">**DevNotify**</td><td>8192</td><td>If set, this enables the caller to receive <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_InputDeviceChange</a> notifications for device arrival and device removal.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawInputDeviceFlags.Exclude">**Exclude**</td><td>16</td><td>If set, this specifies the top level collections to exclude when reading a complete usage page. 

 This flag only affects a TLC whose usage page is already specified with PageOnly.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawInputDeviceFlags.ExInputSink">**ExInputSink**</td><td>4096</td><td>If set, this enables the caller to receive input in the background only if the foreground application does not process it. 

 In other words, if the foreground application is not registered for raw input, then the background application that is registered will receive the input.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawInputDeviceFlags.InputSink">**InputSink**</td><td>256</td><td>If set, this enables the caller to receive the input even when the caller is not in the foreground. 

 Note that <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice_HwndTarget">HwndTarget</a> must be specified.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawInputDeviceFlags.NoHotkeys">**NoHotkeys**</td><td>512</td><td>If set, the application-defined keyboard device hotkeys are not handled. 

 However, the system hotkeys; for example, `ALT`+`TAB` and `CTRL`+`ALT`+`DEL`, are still handled. 

 By default, all keyboard hotkeys are handled. 

NoHotkeys can be specified even if NoLegacy is not specified and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice_HwndTarget">HwndTarget</a> is Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawInputDeviceFlags.NoLegacy">**NoLegacy**</td><td>48</td><td>If set, the application-defined keyboard device hotkeys are not handled. 

 However, the system hotkeys; for example, `ALT`+`TAB` and `CTRL`+`ALT`+`DEL`, are still handled. 

 By default, all keyboard hotkeys are handled. 

NoHotkeys can be specified even if NoLegacy is not specified and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice_HwndTarget">HwndTarget</a> is Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawInputDeviceFlags.PageOnly">**PageOnly**</td><td>32</td><td>If set, this specifies all devices whose top level collection is from the specified <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice_UsagePage">UsagePage</a>. Note that <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice_Usage">Usage</a> must be zero. 

 To exclude a particular top level collection, use Exclude.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawInputDeviceFlags.Remove">**Remove**</td><td>1</td><td>If set, this removes the top level collection from the inclusion list. 

 This tells the operating system to stop reading from a device which matches the top level collection.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms645565%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms645565%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />