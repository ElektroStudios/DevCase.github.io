# TestExecutionInfo.Method Property 
 

Gets the method metadata.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[XmlIgnoreAttribute]
public MethodInfo Method { get; }
```

**VB**<br />
``` VB
<XmlIgnoreAttribute>
Public ReadOnly Property Method As MethodInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As TestExecutionInfo
Dim value As MethodInfo

value = instance.Method

```

**C++**<br />
``` C++
public:
[XmlIgnoreAttribute]
property MethodInfo^ Method {
	MethodInfo^ get ();
}
```

**F#**<br />
``` F#
[<XmlIgnoreAttribute>]
member Method : MethodInfo with get

```


#### Property Value
Type: MethodInfo<br />The method metadata.

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_TestExecutionInfo">TestExecutionInfo Class</a><br /><a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics Namespace</a><br />