# ReflectionUtil.GetMethod Method (Object, String, BindingFlags)
 

Searches for the target method in the specified object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static MethodInfo GetMethod(
	Object obj,
	string methodName,
	BindingFlags bindingFlags = BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic|BindingFlags.FlattenHierarchy|BindingFlags.InvokeMethod
)
```

**VB**<br />
``` VB
Public Shared Function GetMethod ( 
	obj As Object,
	methodName As String,
	Optional bindingFlags As BindingFlags = BindingFlags.Instance Or BindingFlags.Static Or BindingFlags.Public Or BindingFlags.NonPublic Or BindingFlags.FlattenHierarchy Or BindingFlags.InvokeMethod
) As MethodInfo
```

**VB Usage**<br />
``` VB Usage
Dim obj As Object
Dim methodName As String
Dim bindingFlags As BindingFlags
Dim returnValue As MethodInfo

returnValue = ReflectionUtil.GetMethod(obj, 
	methodName, bindingFlags)
```

**C++**<br />
``` C++
public:
static MethodInfo^ GetMethod(
	Object^ obj, 
	String^ methodName, 
	BindingFlags bindingFlags = BindingFlags::Instance|BindingFlags::Static|BindingFlags::Public|BindingFlags::NonPublic|BindingFlags::FlattenHierarchy|BindingFlags::InvokeMethod
)
```

**F#**<br />
``` F#
static member GetMethod : 
        obj : Object * 
        methodName : string * 
        ?bindingFlags : BindingFlags 
(* Defaults:
        let _bindingFlags = defaultArg bindingFlags BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic|BindingFlags.FlattenHierarchy|BindingFlags.InvokeMethod
*)
-> MethodInfo 

```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: System.Object<br />The source object from which to retrieve the method.</dd><dt>methodName</dt><dd>Type: System.String<br />The name of the method to search for.</dd><dt>bindingFlags (Optional)</dt><dd>Type: System.Reflection.BindingFlags<br />Flags that controls binding and the way in which the search for members and types is conducted by Reflection.</dd></dl>

#### Return Value
Type: MethodInfo<br />A MethodInfo instance that represents the resulting method.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim method As MethodInfo = GetMethod(Me, "Hide")
method.Invoke(Me, Nothing)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetMethod">GetMethod Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />