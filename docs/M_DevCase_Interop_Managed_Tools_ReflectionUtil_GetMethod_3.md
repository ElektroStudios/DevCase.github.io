# ReflectionUtil.GetMethod Method (Type, String, Type[])
 

Searches for the target method in the specified Type.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static MethodInfo GetMethod(
	Type type,
	string methodName,
	Type[] types
)
```

**VB**<br />
``` VB
Public Shared Function GetMethod ( 
	type As Type,
	methodName As String,
	types As Type()
) As MethodInfo
```

**VB Usage**<br />
``` VB Usage
Dim type As Type
Dim methodName As String
Dim types As Type()
Dim returnValue As MethodInfo

returnValue = ReflectionUtil.GetMethod(type, 
	methodName, types)
```

**C++**<br />
``` C++
public:
static MethodInfo^ GetMethod(
	Type^ type, 
	String^ methodName, 
	array<Type^>^ types
)
```

**F#**<br />
``` F#
static member GetMethod : 
        type : Type * 
        methodName : string * 
        types : Type[] -> MethodInfo 

```


#### Parameters
&nbsp;<dl><dt>type</dt><dd>Type: System.Type<br />The source type from which to retrieve the method.</dd><dt>methodName</dt><dd>Type: System.String<br />The name of the method to search for.</dd><dt>types</dt><dd>Type: System.Type[]<br />An array of Type objects representing the number, order, and type of the parameters for the method to get. 

 You can specify an empty array of Type objects (as provided by the EmptyTypes field) to get a method that takes no parameters.</dd></dl>

#### Return Value
Type: MethodInfo<br />A MethodInfo instance that represents the resulting method.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim types As Type() = {GetType(Integer), GetType(Integer), GetType(Integer), GetType(Integer)}
Dim params As Object() = {Me.Location.X, Me.Location.Y, CInt(Me.Size.Width * 1.5), CInt(Me.Size.Height * 1.5)}
Dim method As MethodInfo = GetMethod(GetType(Form), "SetBounds", types)
method.Invoke(Me, params)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetMethod">GetMethod Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />