# ProcessUtil.GetProcessPerformanceCounter Method (Process, String)
 

Gets a PerformanceCounter of the categry name "Process" with the specified counter name for the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PerformanceCounter GetProcessPerformanceCounter(
	Process pr,
	string counterName
)
```

**VB**<br />
``` VB
Public Shared Function GetProcessPerformanceCounter ( 
	pr As Process,
	counterName As String
) As PerformanceCounter
```

**VB Usage**<br />
``` VB Usage
Dim pr As Process
Dim counterName As String
Dim returnValue As PerformanceCounter

returnValue = ProcessUtil.GetProcessPerformanceCounter(pr, 
	counterName)
```

**C++**<br />
``` C++
public:
static PerformanceCounter^ GetProcessPerformanceCounter(
	Process^ pr, 
	String^ counterName
)
```

**F#**<br />
``` F#
static member GetProcessPerformanceCounter : 
        pr : Process * 
        counterName : string -> PerformanceCounter 

```


#### Parameters
&nbsp;<dl><dt>pr</dt><dd>Type: System.Diagnostics.Process<br />The process.</dd><dt>counterName</dt><dd>Type: System.String<br />The name of the counter to get (eg. "% Processor Time").</dd></dl>

#### Return Value
Type: PerformanceCounter<br />The resulting PerformanceCounter.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim pr As Process = Process.GetCurrentProcess()
Dim perfCounter As PerformanceCounter = GetProcessPerformanceCounter(pr, "% Processor Time")

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