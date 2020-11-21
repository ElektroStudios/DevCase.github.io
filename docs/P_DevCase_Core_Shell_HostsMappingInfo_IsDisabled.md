# HostsMappingInfo.IsDisabled Property 
 

This value is reserved. Gets a value indicating whether the mapping is disabled in the HOSTS file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool IsDisabled { get; set; }
```

**VB**<br />
``` VB
Public Property IsDisabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As HostsMappingInfo
Dim value As Boolean

value = instance.IsDisabled

instance.IsDisabled = value
```

**C++**<br />
``` C++
public:
property bool IsDisabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member IsDisabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the mapping is disabled, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_HostsMappingInfo">HostsMappingInfo Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />