# ProcessUtil.GetProcessCpuPercentUsage Method (Process)
 

Gets the CPU percentage usage for the specified Process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static float GetProcessCpuPercentUsage(
	Process pr
)
```

**VB**<br />
``` VB
Public Shared Function GetProcessCpuPercentUsage ( 
	pr As Process
) As Single
```

**VB Usage**<br />
``` VB Usage
Dim pr As Process
Dim returnValue As Single

returnValue = ProcessUtil.GetProcessCpuPercentUsage(pr)
```

**C++**<br />
``` C++
public:
static float GetProcessCpuPercentUsage(
	Process^ pr
)
```

**F#**<br />
``` F#
static member GetProcessCpuPercentUsage : 
        pr : Process -> float32 

```


#### Parameters
&nbsp;<dl><dt>pr</dt><dd>Type: System.Diagnostics.Process<br />The Process.</dd></dl>

#### Return Value
Type: Single<br />The resulting CPU percentage usage for the specified Process.

## Remarks
Before calling this method, performance counters must be enabled in the 'app.config' file. See the next example: <configuration> ... <system.net> <settings> <performanceCounters enabled="true"/> </settings> </system.net> ... </configuration>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim pr As Process = Process.GetCurrentProcess()
Dim cpuPercent As Single = GetProcessCpuPercentUsage(pr)
Dim str As String = String.Format("Process Name: {0}; CPU Usage: {1:F2}%", pr.ProcessName, cpuPercent)
Console.WriteLine(str)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessCpuPercentUsage">GetProcessCpuPercentUsage Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />