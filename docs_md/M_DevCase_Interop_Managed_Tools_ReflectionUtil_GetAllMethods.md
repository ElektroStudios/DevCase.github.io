# ReflectionUtil.GetAllMethods Method (Object, Boolean, BindingFlags)
 

Gets all the methods declared in the specified object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<MethodInfo> GetAllMethods(
	Object obj,
	bool includeBaseTypes,
	BindingFlags bindingFlags = BindingFlags.DeclaredOnly|BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic
)
```

**VB**<br />
``` VB
Public Shared Function GetAllMethods ( 
	obj As Object,
	includeBaseTypes As Boolean,
	Optional bindingFlags As BindingFlags = BindingFlags.DeclaredOnly Or BindingFlags.Instance Or BindingFlags.Static Or BindingFlags.Public Or BindingFlags.NonPublic
) As IEnumerable(Of MethodInfo)
```

**VB Usage**<br />
``` VB Usage
Dim obj As Object
Dim includeBaseTypes As Boolean
Dim bindingFlags As BindingFlags
Dim returnValue As IEnumerable(Of MethodInfo)

returnValue = ReflectionUtil.GetAllMethods(obj, 
	includeBaseTypes, bindingFlags)
```

**C++**<br />
``` C++
public:
static IEnumerable<MethodInfo^>^ GetAllMethods(
	Object^ obj, 
	bool includeBaseTypes, 
	BindingFlags bindingFlags = BindingFlags::DeclaredOnly|BindingFlags::Instance|BindingFlags::Static|BindingFlags::Public|BindingFlags::NonPublic
)
```

**F#**<br />
``` F#
static member GetAllMethods : 
        obj : Object * 
        includeBaseTypes : bool * 
        ?bindingFlags : BindingFlags 
(* Defaults:
        let _bindingFlags = defaultArg bindingFlags BindingFlags.DeclaredOnly|BindingFlags.Instance|BindingFlags.Static|BindingFlags.Public|BindingFlags.NonPublic
*)
-> IEnumerable<MethodInfo> 

```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: System.Object<br />The source object from which to retrieve the methods.</dd><dt>includeBaseTypes</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), the search include methods declared in base types too.</dd><dt>bindingFlags (Optional)</dt><dd>Type: System.Reflection.BindingFlags<br />Flags that controls binding and the way in which the search for members and types is conducted by Reflection.</dd></dl>

#### Return Value
Type: IEnumerable(MethodInfo)<br />A IEnumerable(T) collection with all the methods found.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim methods As IEnumerable(Of MethodInfo) = GetAllMethods(Me,
                                                          includeBaseTypes:=False,
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