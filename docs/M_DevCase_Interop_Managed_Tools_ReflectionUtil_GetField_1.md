# ReflectionUtil.GetField Method (Type, String, BindingFlags)
 

Searches for the specified field in the specified type.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static FieldInfo GetField(
	Type type,
	string fieldName,
	BindingFlags bindingFlags = BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic|BindingFlags.FlattenHierarchy|BindingFlags.GetField
)
```

**VB**<br />
``` VB
Public Shared Function GetField ( 
	type As Type,
	fieldName As String,
	Optional bindingFlags As BindingFlags = BindingFlags.Instance Or BindingFlags.Static Or BindingFlags.Public Or BindingFlags.NonPublic Or BindingFlags.FlattenHierarchy Or BindingFlags.GetField
) As FieldInfo
```

**VB Usage**<br />
``` VB Usage
Dim type As Type
Dim fieldName As String
Dim bindingFlags As BindingFlags
Dim returnValue As FieldInfo

returnValue = ReflectionUtil.GetField(type, 
	fieldName, bindingFlags)
```

**C++**<br />
``` C++
public:
static FieldInfo^ GetField(
	Type^ type, 
	String^ fieldName, 
	BindingFlags bindingFlags = BindingFlags::Instance|BindingFlags::Static|BindingFlags::Public|BindingFlags::NonPublic|BindingFlags::FlattenHierarchy|BindingFlags::GetField
)
```

**F#**<br />
``` F#
static member GetField : 
        type : Type * 
        fieldName : string * 
        ?bindingFlags : BindingFlags 
(* Defaults:
        let _bindingFlags = defaultArg bindingFlags BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic|BindingFlags.FlattenHierarchy|BindingFlags.GetField
*)
-> FieldInfo 

```


#### Parameters
&nbsp;<dl><dt>type</dt><dd>Type: System.Type<br />The source type to search for the field.</dd><dt>fieldName</dt><dd>Type: System.String<br />The name of the field to search for.</dd><dt>bindingFlags (Optional)</dt><dd>Type: System.Reflection.BindingFlags<br />Flags that controls binding and the way in which the search for members and types is conducted by Reflection.</dd></dl>

#### Return Value
Type: FieldInfo<br />A FieldInfo instance that represents the obtained field.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim field As FieldInfo = GetField(GetType(Form), "userWindowText")
Dim text As String = DirectCast(field.GetValue(Me), String)

Console.WriteLine(Text)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetField">GetField Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />