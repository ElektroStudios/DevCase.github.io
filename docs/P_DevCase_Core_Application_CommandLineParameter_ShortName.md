# CommandLineParameter.ShortName Property 
 

Gets or sets the short name of the parameter. 

 A short name should be an abbreviated name of the parameter. A short name is optional and can de null.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string ShortName { get; set; }
```

**VB**<br />
``` VB
Public Property ShortName As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineParameter
Dim value As String

value = instance.ShortName

instance.ShortName = value
```

**C++**<br />
``` C++
public:
property String^ ShortName {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member ShortName : string with get, set

```


#### Property Value
Type: String<br />The short name of the parameter.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />