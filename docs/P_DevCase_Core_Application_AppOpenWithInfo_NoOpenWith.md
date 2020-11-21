# AppOpenWithInfo.NoOpenWith Property 
 

Gets or sets a value indicating whether cc. 

 Be aware that if an OpenWithProgIDs subkey has been set for an application by file type, and the ProgID subkey itself does not also have a NoOpenWith entry, that application will appear in the list of recommended or available applications even if it has specified the NoOpenWith entry.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool NoOpenWith { get; set; }
```

**VB**<br />
``` VB
Public Property NoOpenWith As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppOpenWithInfo
Dim value As Boolean

value = instance.NoOpenWith

instance.NoOpenWith = value
```

**C++**<br />
``` C++
public:
property bool NoOpenWith {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member NoOpenWith : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if no application is specified for opening this file type; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_AppOpenWithInfo">AppOpenWithInfo Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />