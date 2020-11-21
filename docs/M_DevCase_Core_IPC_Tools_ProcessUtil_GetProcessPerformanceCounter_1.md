# ProcessUtil.GetProcessPerformanceCounter Method (Int32, String)
 

Gets a PerformanceCounter of the categry name "Process" with the specified counter name for the process with the specified process id (pid).

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PerformanceCounter GetProcessPerformanceCounter(
	int pid,
	string counterName
)
```

**VB**<br />
``` VB
Public Shared Function GetProcessPerformanceCounter ( 
	pid As Integer,
	counterName As String
) As PerformanceCounter
```

**VB Usage**<br />
``` VB Usage
Dim pid As Integer
Dim counterName As String
Dim returnValue As PerformanceCounter

returnValue = ProcessUtil.GetProcessPerformanceCounter(pid, 
	counterName)
```

**C++**<br />
``` C++
public:
static PerformanceCounter^ GetProcessPerformanceCounter(
	int pid, 
	String^ counterName
)
```

**F#**<br />
``` F#
static member GetProcessPerformanceCounter : 
        pid : int * 
        counterName : string -> PerformanceCounter 

```


#### Parameters
&nbsp;<dl><dt>pid</dt><dd>Type: System.Int32<br />The process id.</dd><dt>counterName</dt><dd>Type: System.String<br />The name of the counter to get (eg. "% Processor Time").</dd></dl>

#### Return Value
Type: PerformanceCounter<br />The resulting PerformanceCounter.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim pid As Integer = Process.GetCurrentProcess().Id
Dim perfCounter As PerformanceCounter = GetProcessPerformanceCounter(pid, "% Processor Time")

Dim sample1 As CounterSample = perfCounter.NextSample()
Thread.Sleep(1000)
Dim sample2 As CounterSample = perfCounter.NextSample()
Dim calc As Single = CounterSample.Calculate(sample1, sample2)
Dim cpuAverage As Single = (calc / Environment.ProcessorCount)

Console.WriteLine("Average CPU usage percentage for current process: {0:F2}%", cpuAverage)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPerformanceCounter">GetProcessPerformanceCounter Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />