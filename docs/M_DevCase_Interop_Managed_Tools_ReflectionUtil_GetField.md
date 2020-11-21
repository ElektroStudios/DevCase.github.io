# ReflectionUtil.GetField Method (Object, String, BindingFlags)
 

Searches for the specified field in the specified object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static FieldInfo GetField(
	Object obj,
	string fieldName,
	BindingFlags bindingFlags = BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic|BindingFlags.FlattenHierarchy|BindingFlags.GetField
)
```

**VB**<br />
``` VB
Public Shared Function GetField ( 
	obj As Object,
	fieldName As String,
	Optional bindingFlags As BindingFlags = BindingFlags.Instance Or BindingFlags.Static Or BindingFlags.Public Or BindingFlags.NonPublic Or BindingFlags.FlattenHierarchy Or BindingFlags.GetField
) As FieldInfo
```

**VB Usage**<br />
``` VB Usage
Dim obj As Object
Dim fieldName As String
Dim bindingFlags As BindingFlags
Dim returnValue As FieldInfo

returnValue = ReflectionUtil.GetField(obj, 
	fieldName, bindingFlags)
```

**C++**<br />
``` C++
public:
static FieldInfo^ GetField(
	Object^ obj, 
	String^ fieldName, 
	BindingFlags bindingFlags = BindingFlags::Instance|BindingFlags::Static|BindingFlags::Public|BindingFlags::NonPublic|BindingFlags::FlattenHierarchy|BindingFlags::GetField
)
```

**F#**<br />
``` F#
static member GetField : 
        obj : Object * 
        fieldName : string * 
        ?bindingFlags : BindingFlags 
(* Defaults:
        let _bindingFlags = defaultArg bindingFlags BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic|BindingFlags.FlattenHierarchy|BindingFlags.GetField
*)
-> FieldInfo 

```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: System.Object<br />The source object to search for the field.</dd><dt>fieldName</dt><dd>Type: System.String<br />The name of the field to search for.</dd><dt>bindingFlags (Optional)</dt><dd>Type: System.Reflection.BindingFlags<br />Flags that controls binding and the way in which the search for members and types is conducted by Reflection.</dd></dl>

#### Return Value
Type: FieldInfo<br />A FieldInfo instance that represents the obtained field.

## Examples
This is a code example. 
**VB**<br />
``` VB
' Declare a field.
Public MyField As String = "My Field Value"

' Get the declared field.
Dim field As FieldInfo = GetField(Me, "MyField")
Dim value As String = DirectCast(field.GetValue(Me), String)

Console.WriteLine(value)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetField">GetField Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />