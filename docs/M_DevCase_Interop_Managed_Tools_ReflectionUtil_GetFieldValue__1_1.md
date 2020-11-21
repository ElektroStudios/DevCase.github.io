# ReflectionUtil.GetFieldValue(*T*) Method (Object, String, *T*, BindingFlags)
 

Searches for the specified field in the specified object, and returns the field value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static T GetFieldValue<T>(
	Object obj,
	string fieldName,
	T defaultIfEmpty,
	BindingFlags bindingFlags = BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic|BindingFlags.FlattenHierarchy|BindingFlags.GetProperty
)

```

**VB**<br />
``` VB
Public Shared Function GetFieldValue(Of T) ( 
	obj As Object,
	fieldName As String,
	defaultIfEmpty As T,
	Optional bindingFlags As BindingFlags = BindingFlags.Instance Or BindingFlags.Static Or BindingFlags.Public Or BindingFlags.NonPublic Or BindingFlags.FlattenHierarchy Or BindingFlags.GetProperty
) As T
```

**VB Usage**<br />
``` VB Usage
Dim obj As Object
Dim fieldName As String
Dim defaultIfEmpty As T
Dim bindingFlags As BindingFlags
Dim returnValue As T

returnValue = ReflectionUtil.GetFieldValue(obj, 
	fieldName, defaultIfEmpty, bindingFlags)
```

**C++**<br />
``` C++
public:
generic<typename T>
static T GetFieldValue(
	Object^ obj, 
	String^ fieldName, 
	T defaultIfEmpty, 
	BindingFlags bindingFlags = BindingFlags::Instance|BindingFlags::Static|BindingFlags::Public|BindingFlags::NonPublic|BindingFlags::FlattenHierarchy|BindingFlags::GetProperty
)
```

**F#**<br />
``` F#
static member GetFieldValue : 
        obj : Object * 
        fieldName : string * 
        defaultIfEmpty : 'T * 
        ?bindingFlags : BindingFlags 
(* Defaults:
        let _bindingFlags = defaultArg bindingFlags BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic|BindingFlags.FlattenHierarchy|BindingFlags.GetProperty
*)
-> 'T 

```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: System.Object<br />The source object from which to retrieve the field.</dd><dt>fieldName</dt><dd>Type: System.String<br />The name of the field to search for.</dd><dt>defaultIfEmpty</dt><dd>Type: *T*<br />The default value to return in case of the property value is a null reference (`Nothing` in Visual Basic).</dd><dt>bindingFlags (Optional)</dt><dd>Type: System.Reflection.BindingFlags<br />Flags that controls binding and the way in which the search for members and types is conducted by Reflection.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the field to be returned.</dd></dl>

#### Return Value
Type: *T*<br />The field value.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td /></tr><tr><td>ArgumentException</td><td>Field not found using the current flags.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
' Declare a field
Public MyField As String = Nothing

' Get the declared field
Dim field As String = GetFieldValue(Of String)(Me, "MyField", "Default value if null")
Console.WriteLine(field)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetFieldValue">GetFieldValue Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />