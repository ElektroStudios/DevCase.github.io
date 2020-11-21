# VisualStudioUtil.IsVisualStudioInstalled Method (VisualStudioVersion)
 

Determines whether a specific version of Visual Studio is installed in the current machine.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsVisualStudioInstalled(
	VisualStudioVersion version
)
```

**VB**<br />
``` VB
Public Shared Function IsVisualStudioInstalled ( 
	version As VisualStudioVersion
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim version As VisualStudioVersion
Dim returnValue As Boolean

returnValue = VisualStudioUtil.IsVisualStudioInstalled(version)
```

**C++**<br />
``` C++
public:
static bool IsVisualStudioInstalled(
	VisualStudioVersion version
)
```

**F#**<br />
``` F#
static member IsVisualStudioInstalled : 
        version : VisualStudioVersion -> bool 

```


#### Parameters
&nbsp;<dl><dt>version</dt><dd>Type: <a href="T_DevCase_Interop_Managed_VisualStudioVersion">DevCase.Interop.Managed.VisualStudioVersion</a><br />The Visual Studio version to check.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified version of Visual Studio is installed in the current machine; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isVisualStudio2017Installed As Boolean = IsVisualStudioInstalled(VisualStudioVersion.Vs2017)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_VisualStudioUtil">VisualStudioUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_VisualStudioUtil_IsVisualStudioInstalled">IsVisualStudioInstalled Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />