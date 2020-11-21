# ReflectionUtil.TypeHasPublicDefaultConstructor Method 
 

Determines whether the source Type has defined a public default parameterless constructor.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool TypeHasPublicDefaultConstructor(
	Type type
)
```

**VB**<br />
``` VB
Public Shared Function TypeHasPublicDefaultConstructor ( 
	type As Type
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim type As Type
Dim returnValue As Boolean

returnValue = ReflectionUtil.TypeHasPublicDefaultConstructor(type)
```

**C++**<br />
``` C++
public:
static bool TypeHasPublicDefaultConstructor(
	Type^ type
)
```

**F#**<br />
``` F#
static member TypeHasPublicDefaultConstructor : 
        type : Type -> bool 

```


#### Parameters
&nbsp;<dl><dt>type</dt><dd>Type: System.Type<br />The source Type.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if the source Type has defined a public default parameterless constructor; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim type As Type = GetType(Rectangle)
Dim result As Boolean = TypeHasPublicDefaultConstructor(type)
Console.WriteLine(result)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />