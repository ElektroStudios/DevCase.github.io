# NetworkTrafficMonitor.GetAvailableInterfaceNames Method 
 

Gets the available network interface names.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<string> GetAvailableInterfaceNames()
```

**VB**<br />
``` VB
Public Shared Function GetAvailableInterfaceNames As IEnumerable(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As IEnumerable(Of String)

returnValue = NetworkTrafficMonitor.GetAvailableInterfaceNames()
```

**C++**<br />
``` C++
public:
static IEnumerable<String^>^ GetAvailableInterfaceNames()
```

**F#**<br />
``` F#
static member GetAvailableInterfaceNames : unit -> IEnumerable<string> 

```


#### Return Value
Type: IEnumerable(String)<br />An IEnumerable(T) that enumerates the available network interface names.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_NetworkTrafficMonitor">NetworkTrafficMonitor Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />