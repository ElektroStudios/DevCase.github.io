# ProcessStartupInfoFlags Enumeration
 

Flags for <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> member.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ProcessStartupInfoFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ProcessStartupInfoFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessStartupInfoFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ProcessStartupInfoFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ProcessStartupInfoFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessStartupInfoFlags.UseShowWindow">**UseShowWindow**</td><td>1</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_ShowWindow">ShowWindow</a> member contain additional information.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessStartupInfoFlags.UseSize">**UseSize**</td><td>2</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_SizeX">SizeX</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_SizeY">SizeY</a> members contain additional information.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessStartupInfoFlags.usePosition">**usePosition**</td><td>4</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_PositionX">PositionX</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_PositionY">PositionY</a> members contain additional information.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessStartupInfoFlags.UseCountChars">**UseCountChars**</td><td>8</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_CountCharsX">CountCharsX</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_CountCharsY">CountCharsY</a> members contain additional information.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessStartupInfoFlags.UseFillAttribute">**UseFillAttribute**</td><td>16</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_FillAttribute">FillAttribute</a> member contain additional information.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessStartupInfoFlags.RunFullscreen">**RunFullscreen**</td><td>32</td><td>Indicates that the process should be run in full-screen mode, rather than in windowed mode. 

 This flag is only valid for console applications running on an x86 computer.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessStartupInfoFlags.ForceOnFeedback">**ForceOnFeedback**</td><td>64</td><td>Indicates that the cursor is in feedback mode for two seconds after CreateProcess is called. The Working in Background cursor is displayed (see the Pointers tab in the Mouse control panel utility). 

 If during those two seconds the process makes the first GUI call, the system gives five more seconds to the process. If during those five seconds the process shows a window, the system gives five more seconds to the process to finish drawing the window. 

 The system turns the feedback cursor off after the first call to GetMessage, regardless of whether the process is drawing.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessStartupInfoFlags.ForceOffFeedback">**ForceOffFeedback**</td><td>128</td><td>Indicates that the feedback cursor is forced off while the process is starting. The Normal Select cursor is displayed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessStartupInfoFlags.UseStdHandles">**UseStdHandles**</td><td>256</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_StdInput">StdInput</a>, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_StdOutput">StdOutput</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_StdError">StdError</a> members contain additional information. 

 If this flag is specified when calling one of the process creation functions, the handles must be inheritable and the function's bInheritHandles parameter must be set to `true` (`True` in Visual Basic). 

 If this flag is specified when calling the GetStartupInfo function, these members are either the handle value specified during process creation or Zero (INVALID_HANDLE_VALUE). 

 Handles must be closed with CloseHandle when they are no longer needed. 

 This flag cannot be used with UseHotkey.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessStartupInfoFlags.UseHotkey">**UseHotkey**</td><td>512</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_StdInput">StdInput</a> member contain additional information. 

 This flag cannot be used with UseStdHandles.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessStartupInfoFlags.PreventPinning">**PreventPinning**</td><td>8192</td><td>Indicates that any windows created by the process cannot be pinned on the taskbar 

 This flag must be combined with TitleIsAppId.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessStartupInfoFlags.TitleIsAppId">**TitleIsAppId**</td><td>4096</td><td>The lpTitle member contains an AppUserModelID. This identifier controls how the taskbar and Start menu present the application, and enables it to be associated with the correct shortcuts and Jump Lists. 

 Generally, applications will use the SetCurrentProcessExplicitAppUserModelID and GetCurrentProcessExplicitAppUserModelID functions instead of setting this flag. 

 If PreventPinning is used, application windows cannot be pinned on the taskbar. The use of any AppUserModelID-related window properties by the application overrides this setting for that window only. 

 This flag must be combined with TitleIsLinkName.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessStartupInfoFlags.TitleIsLinkName">**TitleIsLinkName**</td><td>2048</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Title">Title</a> member contains the path of the shortcut file (.lnk) that the user invoked to start this process. 

 This is typically set by the shell when a .lnk file pointing to the launched application is invoked. 

 Most applications will not need to set this value. 

 This flag must be combined with TitleIsAppId.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessStartupInfoFlags.UntrustedSource">**UntrustedSource**</td><td>32768</td><td>The command line came from an untrusted source.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/ns-processthreadsapi-_startupinfoa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/ns-processthreadsapi-_startupinfoa</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />