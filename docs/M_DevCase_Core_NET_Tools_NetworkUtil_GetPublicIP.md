# NetworkUtil.GetPublicIP Method 
 

Gets the public IP address of the current machine.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IPAddress GetPublicIP()
```

**VB**<br />
``` VB
Public Shared Function GetPublicIP As IPAddress
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As IPAddress

returnValue = NetworkUtil.GetPublicIP()
```

**C++**<br />
``` C++
public:
static IPAddress^ GetPublicIP()
```

**F#**<br />
``` F#
static member GetPublicIP : unit -> IPAddress 

```


#### Return Value
Type: IPAddress<br />The resulting IP address.

## Remarks
<a href="http://checkip.dyndns.org/" target="_blank">http://checkip.dyndns.org/</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim ip As IPAddress = GetPublicIP()
Console.WriteLine(ip.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_NetworkUtil">NetworkUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />