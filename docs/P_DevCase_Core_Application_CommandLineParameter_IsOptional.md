# CommandLineParameter.IsOptional Property 
 

Gets or sets a value indicating whether this parameter is required for the application. 

 A value of `false` (`False` in Visual Basic) means the user needs to pass this parameter to the application. 

 A value of `true` (`True` in Visual Basic) means this is an optional parameter so no matter if the user pass this parameter to the application.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool IsOptional { get; set; }
```

**VB**<br />
``` VB
Public Property IsOptional As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineParameter
Dim value As Boolean

value = instance.IsOptional

instance.IsOptional = value
```

**C++**<br />
``` C++
public:
property bool IsOptional {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member IsOptional : bool with get, set

```


#### Property Value
Type: Boolean<br />`false` (`False` in Visual Basic) if this parameter is required for the application; otherwise, `true` (`True` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />