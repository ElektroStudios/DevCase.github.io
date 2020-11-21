# ReflectionUtil.GetPropertyValue(*T*) Method (Object, String, *T*, BindingFlags)
 

Searches for the specified property in the specified object, and returns the property value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static T GetPropertyValue<T>(
	Object obj,
	string propName,
	T defaultIfEmpty,
	BindingFlags bindingFlags = BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic|BindingFlags.FlattenHierarchy|BindingFlags.GetProperty
)

```

**VB**<br />
``` VB
Public Shared Function GetPropertyValue(Of T) ( 
	obj As Object,
	propName As String,
	defaultIfEmpty As T,
	Optional bindingFlags As BindingFlags = BindingFlags.Instance Or BindingFlags.Static Or BindingFlags.Public Or BindingFlags.NonPublic Or BindingFlags.FlattenHierarchy Or BindingFlags.GetProperty
) As T
```

**VB Usage**<br />
``` VB Usage
Dim obj As Object
Dim propName As String
Dim defaultIfEmpty As T
Dim bindingFlags As BindingFlags
Dim returnValue As T

returnValue = ReflectionUtil.GetPropertyValue(obj, 
	propName, defaultIfEmpty, bindingFlags)
```

**C++**<br />
``` C++
public:
generic<typename T>
static T GetPropertyValue(
	Object^ obj, 
	String^ propName, 
	T defaultIfEmpty, 
	BindingFlags bindingFlags = BindingFlags::Instance|BindingFlags::Static|BindingFlags::Public|BindingFlags::NonPublic|BindingFlags::FlattenHierarchy|BindingFlags::GetProperty
)
```

**F#**<br />
``` F#
static member GetPropertyValue : 
        obj : Object * 
        propName : string * 
        defaultIfEmpty : 'T * 
        ?bindingFlags : BindingFlags 
(* Defaults:
        let _bindingFlags = defaultArg bindingFlags BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic|BindingFlags.FlattenHierarchy|BindingFlags.GetProperty
*)
-> 'T 

```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: System.Object<br />The source object from which to retrieve the property.</dd><dt>propName</dt><dd>Type: System.String<br />The name of the property to search for.</dd><dt>defaultIfEmpty</dt><dd>Type: *T*<br />The default value to return in case of the property value is a null reference (`Nothing` in Visual Basic).</dd><dt>bindingFlags (Optional)</dt><dd>Type: System.Reflection.BindingFlags<br />Flags that controls binding and the way in which the search for members and types is conducted by Reflection.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the property to be returned.</dd></dl>

#### Return Value
Type: *T*<br />The property value.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td /></tr><tr><td>ArgumentException</td><td>Property not found using the current flags.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim text As String = GetPropertyValue(Of String)(Me, "Text", String.Empty)

Console.WriteLine(text)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetPropertyValue">GetPropertyValue Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />