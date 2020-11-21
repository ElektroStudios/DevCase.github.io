# ReflectionUtil.GetProperty Method (Type, String, BindingFlags)
 

Searches for the specified property in the specified Type.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PropertyInfo GetProperty(
	Type type,
	string propName,
	BindingFlags bindingFlags = BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic|BindingFlags.FlattenHierarchy|BindingFlags.GetProperty
)
```

**VB**<br />
``` VB
Public Shared Function GetProperty ( 
	type As Type,
	propName As String,
	Optional bindingFlags As BindingFlags = BindingFlags.Instance Or BindingFlags.Static Or BindingFlags.Public Or BindingFlags.NonPublic Or BindingFlags.FlattenHierarchy Or BindingFlags.GetProperty
) As PropertyInfo
```

**VB Usage**<br />
``` VB Usage
Dim type As Type
Dim propName As String
Dim bindingFlags As BindingFlags
Dim returnValue As PropertyInfo

returnValue = ReflectionUtil.GetProperty(type, 
	propName, bindingFlags)
```

**C++**<br />
``` C++
public:
static PropertyInfo^ GetProperty(
	Type^ type, 
	String^ propName, 
	BindingFlags bindingFlags = BindingFlags::Instance|BindingFlags::Static|BindingFlags::Public|BindingFlags::NonPublic|BindingFlags::FlattenHierarchy|BindingFlags::GetProperty
)
```

**F#**<br />
``` F#
static member GetProperty : 
        type : Type * 
        propName : string * 
        ?bindingFlags : BindingFlags 
(* Defaults:
        let _bindingFlags = defaultArg bindingFlags BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic|BindingFlags.FlattenHierarchy|BindingFlags.GetProperty
*)
-> PropertyInfo 

```


#### Parameters
&nbsp;<dl><dt>type</dt><dd>Type: System.Type<br />The source type to search for the property.</dd><dt>propName</dt><dd>Type: System.String<br />The name of the property to search for.</dd><dt>bindingFlags (Optional)</dt><dd>Type: System.Reflection.BindingFlags<br />Flags that controls binding and the way in which the search for members and types is conducted by Reflection.</dd></dl>

#### Return Value
Type: PropertyInfo<br />A PropertyInfo instance that represents the obtained property.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td /></tr><tr><td>ArgumentException</td><td>Property not found using the current flags.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim prop As PropertyInfo = GetProperty(GetType(Form), "Text")
Dim text As String = DirectCast(prop.GetValue(Me), String)

Console.WriteLine(text)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetProperty">GetProperty Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />