# ReflectionUtil.GetAllMethods(*T*) Method (Boolean, BindingFlags)
 

Gets all the methods declared in the specified Type.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<MethodInfo> GetAllMethods<T>(
	bool includeBaseTypes,
	BindingFlags bindingFlags = BindingFlags.DeclaredOnly|BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic
)

```

**VB**<br />
``` VB
Public Shared Function GetAllMethods(Of T) ( 
	includeBaseTypes As Boolean,
	Optional bindingFlags As BindingFlags = BindingFlags.DeclaredOnly Or BindingFlags.Instance Or BindingFlags.Static Or BindingFlags.Public Or BindingFlags.NonPublic
) As IEnumerable(Of MethodInfo)
```

**VB Usage**<br />
``` VB Usage
Dim includeBaseTypes As Boolean
Dim bindingFlags As BindingFlags
Dim returnValue As IEnumerable(Of MethodInfo)

returnValue = ReflectionUtil.GetAllMethods(includeBaseTypes, 
	bindingFlags)
```

**C++**<br />
``` C++
public:
generic<typename T>
static IEnumerable<MethodInfo^>^ GetAllMethods(
	bool includeBaseTypes, 
	BindingFlags bindingFlags = BindingFlags::DeclaredOnly|BindingFlags::Instance|BindingFlags::Static|BindingFlags::Public|BindingFlags::NonPublic
)
```

**F#**<br />
``` F#
static member GetAllMethods : 
        includeBaseTypes : bool * 
        ?bindingFlags : BindingFlags 
(* Defaults:
        let _bindingFlags = defaultArg bindingFlags BindingFlags.DeclaredOnly|BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic
*)
-> IEnumerable<MethodInfo> 

```


#### Parameters
&nbsp;<dl><dt>includeBaseTypes</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), the search include methods declared in base types too.</dd><dt>bindingFlags (Optional)</dt><dd>Type: System.Reflection.BindingFlags<br />Flags that controls binding and the way in which the search for members and types is conducted by Reflection.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The source type from which to retrieve the methods.</dd></dl>

#### Return Value
Type: IEnumerable(MethodInfo)<br />A IEnumerable(T) collection with all the methods found.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim methods As IEnumerable(Of MethodInfo) = 
    GetAllMethods(Of Form)(includeBaseTypes:=False,
                                             bindingFlags:=BindingFlags.Public Or
                                                           BindingFlags.Static Or
                                                           BindingFlags.Instance)

For Each method As MethodInfo In methods
    Dim params As ParameterInfo() = method.GetParameters()
    Dim paramTypes As IEnumerable(Of Type) = params.Select(Function(param As ParameterInfo) param.ParameterType)
    Dim genericTypes As IEnumerable(Of Type) = method.GetGenericArguments()
    Dim returnType As Type = method.ReturnType
    Dim methodSignature As String = String.Format("{0}{1}({2}){3}",
                                                  method.Name,
                                                  If(genericTypes.Count <> 0, String.Format("(Of {0})", String.Join(", ", genericTypes)), Nothing),
                                                  String.Join(", ", paramTypes),
                                                  If(returnType IsNot GetType(System.Void), String.Format(" As {0}", returnType.ToString()), Nothing))

    Console.WriteLine(methodSignature)
Next method
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_ReflectionUtil_GetAllMethods">GetAllMethods Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />