# ProcessTrafficMonitor Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_NET_ProcessTrafficMonitor">ProcessTrafficMonitor</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ProcessTrafficMonitor(
	int processId
)
```

**VB**<br />
``` VB
Public Sub New ( 
	processId As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim processId As Integer

Dim instance As New ProcessTrafficMonitor(processId)
```

**C++**<br />
``` C++
public:
ProcessTrafficMonitor(
	int processId
)
```

**F#**<br />
``` F#
new : 
        processId : int -> ProcessTrafficMonitor
```


#### Parameters
&nbsp;<dl><dt>processId</dt><dd>Type: System.Int32<br />The PID of the process to monitor. 

 Note that the process should have the performance counters feature enabled to be able to use the counters.</dd></dl>

## Remarks
The application's configuration file (app.config) should look like this: 


**VB**<br />
``` VB
<configuration>
...
  <system.net>
    <settings>
      <performanceCounters enabled="true"/>
    </settings>
  </system.net>
...
</configuration>
```


 MSDN Documentation: <a href="https://msdn.microsoft.com/en-us/library/ms229151%28v=vs.110%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/ms229151%28v=vs.110%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_ProcessTrafficMonitor">ProcessTrafficMonitor Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />