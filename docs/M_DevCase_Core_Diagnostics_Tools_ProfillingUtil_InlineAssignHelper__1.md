# ProfillingUtil.InlineAssignHelper(*T*) Method (*T*, *T*)
 

Helper function that assigns *value* to *refTarget*, then returns *value*.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static T InlineAssignHelper<T>(
	ref T refTarget,
	T value
)

```

**VB**<br />
``` VB
Public Shared Function InlineAssignHelper(Of T) ( 
	ByRef refTarget As T,
	value As T
) As T
```

**VB Usage**<br />
``` VB Usage
Dim refTarget As T
Dim value As T
Dim returnValue As T

returnValue = ProfillingUtil.InlineAssignHelper(refTarget, 
	value)
```

**C++**<br />
``` C++
public:
generic<typename T>
static T InlineAssignHelper(
	T% refTarget, 
	T value
)
```

**F#**<br />
``` F#
static member InlineAssignHelper : 
        refTarget : 'T byref * 
        value : 'T -> 'T 

```


#### Parameters
&nbsp;<dl><dt>refTarget</dt><dd>Type: *T*<br />The target by reference value.</dd><dt>value</dt><dd>Type: *T*<br />The value to return.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: *T*<br />The value returned is *value*.

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_ProfillingUtil">ProfillingUtil Class</a><br /><a href="Overload_DevCase_Core_Diagnostics_Tools_ProfillingUtil_InlineAssignHelper">InlineAssignHelper Overload</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />