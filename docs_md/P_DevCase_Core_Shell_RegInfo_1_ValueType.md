# RegInfo(*T*).ValueType Property 
 

Gets or sets the type of the registry value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public RegistryValueKind ValueType { get; set; }
```

**VB**<br />
``` VB
Public Property ValueType As RegistryValueKind
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As RegInfo
Dim value As RegistryValueKind

value = instance.ValueType

instance.ValueType = value
```

**C++**<br />
``` C++
public:
property RegistryValueKind ValueType {
	RegistryValueKind get ();
	void set (RegistryValueKind value);
}
```

**F#**<br />
``` F#
member ValueType : RegistryValueKind with get, set

```


#### Property Value
Type: RegistryValueKind<br />The type of the registry value.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_RegInfo_1">RegInfo(T) Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />