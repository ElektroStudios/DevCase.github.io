# ProfillingUtil.InlineAssignHelper Method (Object, Object)
 

Helper function that assigns *value* to *refTarget*, then returns *value*.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Object InlineAssignHelper(
	ref Object refTarget,
	Object value
)
```

**VB**<br />
``` VB
Public Shared Function InlineAssignHelper ( 
	ByRef refTarget As Object,
	value As Object
) As Object
```

**VB Usage**<br />
``` VB Usage
Dim refTarget As Object
Dim value As Object
Dim returnValue As Object

returnValue = ProfillingUtil.InlineAssignHelper(refTarget, 
	value)
```

**C++**<br />
``` C++
public:
static Object^ InlineAssignHelper(
	Object^% refTarget, 
	Object^ value
)
```

**F#**<br />
``` F#
static member InlineAssignHelper : 
        refTarget : Object byref * 
        value : Object -> Object 

```


#### Parameters
&nbsp;<dl><dt>refTarget</dt><dd>Type: System.Object<br />The target by reference value.</dd><dt>value</dt><dd>Type: System.Object<br />The value to return.</dd></dl>

#### Return Value
Type: Object<br />The value returned is *value*.

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_ProfillingUtil">ProfillingUtil Class</a><br /><a href="Overload_DevCase_Core_Diagnostics_Tools_ProfillingUtil_InlineAssignHelper">InlineAssignHelper Overload</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />