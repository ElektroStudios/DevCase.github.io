# ProcessUtil.GetProcessCpuPercentUsage Method (Int32)
 

Gets the CPU percentage usage for the process with the specified process id (pid).

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static float GetProcessCpuPercentUsage(
	int pid
)
```

**VB**<br />
``` VB
Public Shared Function GetProcessCpuPercentUsage ( 
	pid As Integer
) As Single
```

**VB Usage**<br />
``` VB Usage
Dim pid As Integer
Dim returnValue As Single

returnValue = ProcessUtil.GetProcessCpuPercentUsage(pid)
```

**C++**<br />
``` C++
public:
static float GetProcessCpuPercentUsage(
	int pid
)
```

**F#**<br />
``` F#
static member GetProcessCpuPercentUsage : 
        pid : int -> float32 

```


#### Parameters
&nbsp;<dl><dt>pid</dt><dd>Type: System.Int32<br />The process id.</dd></dl>

#### Return Value
Type: Single<br />The resulting CPU percentage usage for the process with the specified process id (pid).

## Remarks
Before calling this method, performance counters must be enabled in the 'app.config' file. See the next example: <configuration> ... <system.net> <settings> <performanceCounters enabled="true"/> </settings> </system.net> ... </configuration>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim pr As Process = Process.GetCurrentProcess()
Dim cpuPercent As Single = GetProcessCpuPercentUsage(pr.Id)
Dim str As String = String.Format("Process Name: {0}; CPU Usage: {1:F2}%", pr.ProcessName, cpuPercent)
Console.WriteLine(str)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessCpuPercentUsage">GetProcessCpuPercentUsage Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />