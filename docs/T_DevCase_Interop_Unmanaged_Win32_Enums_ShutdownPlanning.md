# ShutdownPlanning Enumeration
 

Flags combination for `dwReason` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ExitWindowsEx">ExitWindowsEx(ExitwindowsExFlags, ShutdownReason)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_InitiateShutdown">InitiateShutdown(String, String, Int32, UInt32, UInt32)</a> functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ShutdownPlanning
```

**VB**<br />
``` VB
Public Enumeration ShutdownPlanning
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShutdownPlanning
```

**C++**<br />
``` C++
public enum class ShutdownPlanning
```

**F#**<br />
``` F#
type ShutdownPlanning
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShutdownPlanning.Unplanned">**Unplanned**</td><td>0</td><td>The shutdown was unplanned. 

 This is the default parameter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShutdownPlanning.UserDefined">**UserDefined**</td><td>1073741824</td><td>The reason code is defined by the user. 

 If this flag is not present, the reason code is defined by the system. For more information, see Defining a Custom Reason Code.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShutdownPlanning.Planned">**Planned**</td><td>2147483648</td><td>The shutdown was planned. 

 If this flag is not present, the shutdown was unplanned. 

 The system generates a System State Data (SSD) file. This file contains system state information such as the processes, threads, memory usage, and configuration.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa376885%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa376885%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />