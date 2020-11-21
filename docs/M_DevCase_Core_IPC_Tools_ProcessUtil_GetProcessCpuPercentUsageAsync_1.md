# ProcessUtil.GetProcessCpuPercentUsageAsync Method (Int32)
 

Asynchronously gets the CPU percentage usage for the specified Process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task<double> GetProcessCpuPercentUsageAsync(
	int pid
)
```

**VB**<br />
``` VB
Public Shared Function GetProcessCpuPercentUsageAsync ( 
	pid As Integer
) As Task(Of Double)
```

**VB Usage**<br />
``` VB Usage
Dim pid As Integer
Dim returnValue As Task(Of Double)

returnValue = ProcessUtil.GetProcessCpuPercentUsageAsync(pid)
```

**C++**<br />
``` C++
public:
static Task<double>^ GetProcessCpuPercentUsageAsync(
	int pid
)
```

**F#**<br />
``` F#
static member GetProcessCpuPercentUsageAsync : 
        pid : int -> Task<float> 

```


#### Parameters
&nbsp;<dl><dt>pid</dt><dd>Type: System.Int32<br />Theprocess id.</dd></dl>

#### Return Value
Type: Task(Double)<br />The resulting CPU percentage usage for the specified Process.

## Remarks
Before calling this method, performance counters must be enabled in the 'app.config' file. See the next example: <configuration> ... <system.net> <settings> <performanceCounters enabled="true"/> </settings> </system.net> ... </configuration>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim pr As Process = Process.GetCurrentProcess()
Dim cpuPercent As Single = Await GetProcessCpuPercentUsageAsync(pr.Id)
Dim str As String = String.Format("Process Name: {0}; CPU Usage: {1:F2}%", pr.ProcessName, cpuPercent)
Console.WriteLine(str)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessCpuPercentUsageAsync">GetProcessCpuPercentUsageAsync Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />