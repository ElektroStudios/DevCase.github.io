# ReflectionUtil.GetMethod Method (Type, String, BindingFlags)
 

Searches for the target method in the specified Type.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static MethodInfo GetMethod(
	Type type,
	string methodName,
	BindingFlags bindingFlags = BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic|BindingFlags.FlattenHierarchy|BindingFlags.InvokeMethod
)
```

**VB**<br />
``` VB
Public Shared Function GetMethod ( 
	type As Type,
	methodName As String,
	Optional bindingFlags As BindingFlags = BindingFlags.Instance Or BindingFlags.Static Or BindingFlags.Public Or BindingFlags.NonPublic Or BindingFlags.FlattenHierarchy Or BindingFlags.InvokeMethod
) As MethodInfo
```

**VB Usage**<br />
``` VB Usage
Dim type As Type
Dim methodName As String
Dim bindingFlags As BindingFlags
Dim returnValue As MethodInfo

returnValue = ReflectionUtil.GetMethod(type, 
	methodName, bindingFlags)
```

**C++**<br />
``` C++
public:
static MethodInfo^ GetMethod(
	Type^ type, 
	String^ methodName, 
	BindingFlags bindingFlags = BindingFlags::Instance|BindingFlags::Static|BindingFlags::Public|BindingFlags::NonPublic|BindingFlags::FlattenHierarchy|BindingFlags::InvokeMethod
)
```

**F#**<br />
``` F#
static member GetMethod : 
        type : Type * 
        methodName : string * 
        ?bindingFlags : BindingFlags 
(* Defaults:
        let _bindingFlags = defaultArg bindingFlags BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic|BindingFlags.FlattenHierarchy|BindingFlags.InvokeMethod
*)
-> MethodInfo 

```


#### Parameters
&nbsp;<dl><dt>type</dt><dd>Type: System.Type<br />The source type from which to retrieve its properties.</dd><dt>methodName</dt><dd>Type: System.String<br />The name of the method to search for.</dd><dt>bindingFlags (Optional)</dt><dd>Type: System.Reflection.BindingFlags<br />Flags that controls binding and the way in which the search for members and types is conducted by Reflection.</dd></dl>

#### Return Value
Type: MethodInfo<br />A MethodInfo instance that represents the resulting method.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim method As MethodInfo = GetMethod(GetType(Form), "Hide")
method.Invoke(Me, Nothing)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetMethod">GetMethod Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />