# NetworkUtil.NetworkStatusChanged Event
 

Occurs when the state of Internet connectivity changes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static event NetworkStatusChangedEventArgs.NetworkStatusChangedDelegate NetworkStatusChanged
```

**VB**<br />
``` VB
Public Shared Event NetworkStatusChanged As NetworkStatusChangedEventArgs.NetworkStatusChangedDelegate
```

**VB Usage**<br />
``` VB Usage
Dim handler As NetworkStatusChangedEventArgs.NetworkStatusChangedDelegate

AddHandler NetworkUtil.NetworkStatusChanged, handler

```

**C++**<br />
``` C++
public:
static  event NetworkStatusChangedEventArgs.NetworkStatusChangedDelegate^ NetworkStatusChanged {
	void add (NetworkStatusChangedEventArgs.NetworkStatusChangedDelegate^ value);
	void remove (NetworkStatusChangedEventArgs.NetworkStatusChangedDelegate^ value);
}
```

**F#**<br />
``` F#
member NetworkStatusChanged : IEvent<NetworkStatusChangedEventArgs.NetworkStatusChangedDelegate,
    NetworkStatusChangedEventArgs>

```


#### Value
Type: <a href="T_DevCase_Core_NET_Eventing_NetworkStatusChangedEventArgs_NetworkStatusChangedDelegate">DevCase.Core.NET.Eventing.NetworkStatusChangedEventArgs.NetworkStatusChangedDelegate</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1

    Private Sub Form1_Shown() Handles MyBase.Load

        AddHandler NetworkStatusChanged, AddressOf DoNetworkStatusChanged

    End Sub

    Private Sub DoNetworkStatusChanged(ByVal sender As Object, e As NetworkStatusChangedEventArgs)

        If e.IsAvailable Then
            Console.WriteLine("Network is available.")

        Else
            Console.WriteLine("Network is not available.")

        End If

    End Sub

End Class
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_NetworkUtil">NetworkUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />