# RegInfo(*T*).ValueData Property 
 

Gets or sets the data of the registry value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual T ValueData { get; set; }
```

**VB**<br />
``` VB
Public Overridable Property ValueData As T
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As RegInfo
Dim value As T

value = instance.ValueData

instance.ValueData = value
```

**C++**<br />
``` C++
public:
virtual property T ValueData {
	T get ();
	void set (T value);
}
```

**F#**<br />
``` F#
abstract ValueData : 'T with get, set
override ValueData : 'T with get, set
```


#### Property Value
Type: <a href="T_DevCase_Core_Shell_RegInfo_1">*T*</a><br />The data of the registry value.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_RegInfo_1">RegInfo(T) Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />