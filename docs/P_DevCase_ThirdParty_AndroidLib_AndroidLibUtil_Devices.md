# AndroidLibUtil.Devices Property 
 

Gets the Android devices that are connected on the current system.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_AndroidLib">DevCase.ThirdParty.AndroidLib</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<Device> Devices { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property Devices As ReadOnlyCollection(Of Device)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As ReadOnlyCollection(Of Device)

value = AndroidLibUtil.Devices

```

**C++**<br />
``` C++
public:
static property ReadOnlyCollection<Device^>^ Devices {
	ReadOnlyCollection<Device^>^ get ();
}
```

**F#**<br />
``` F#
static member Devices : ReadOnlyCollection<Device> with get

```


#### Property Value
Type: ReadOnlyCollection(Device)<br />The Android devices that are connected on the current system.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_AndroidLib_AndroidLibUtil">AndroidLibUtil Class</a><br /><a href="N_DevCase_ThirdParty_AndroidLib">DevCase.ThirdParty.AndroidLib Namespace</a><br />