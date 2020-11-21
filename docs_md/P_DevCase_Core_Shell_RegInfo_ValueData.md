# RegInfo.ValueData Property 
 

Gets or sets the data of the registry value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override Object ValueData { get; set; }
```

**VB**<br />
``` VB
Public Overrides Property ValueData As Object
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As RegInfo
Dim value As Object

value = instance.ValueData

instance.ValueData = value
```

**C++**<br />
``` C++
public:
virtual property Object^ ValueData {
	Object^ get () override;
	void set (Object^ value) override;
}
```

**F#**<br />
``` F#
abstract ValueData : Object with get, set
override ValueData : Object with get, set
```


#### Property Value
Type: Object<br />The data of the registry value.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_RegInfo">RegInfo Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />