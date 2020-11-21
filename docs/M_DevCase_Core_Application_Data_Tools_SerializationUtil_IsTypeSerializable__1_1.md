# SerializationUtil.IsTypeSerializable(*T*) Method (*T*)
 

Determines whether the specified Type can be serialized.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsTypeSerializable<T>(
	T type
)

```

**VB**<br />
``` VB
Public Shared Function IsTypeSerializable(Of T) ( 
	type As T
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim type As T
Dim returnValue As Boolean

returnValue = SerializationUtil.IsTypeSerializable(type)
```

**C++**<br />
``` C++
public:
generic<typename T>
static bool IsTypeSerializable(
	T type
)
```

**F#**<br />
``` F#
static member IsTypeSerializable : 
        type : 'T -> bool 

```


#### Parameters
&nbsp;<dl><dt>type</dt><dd>Type: *T*<br />The Type to check.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified Type can be serialized; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As Boolean = IsTypeSerializable(GetType(Bitmap))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_SerializationUtil">SerializationUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_SerializationUtil_IsTypeSerializable">IsTypeSerializable Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />