# ReflectionUtil.GetAllBaseTypes(*T*) Method 
 

Gets the Type inheritance hierarchy of the the source Type, that is, the type from which the source Type directly inherits, and the types from which their inherited types inherits.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<Type> GetAllBaseTypes<T>()

```

**VB**<br />
``` VB
Public Shared Function GetAllBaseTypes(Of T) As IEnumerable(Of Type)
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As IEnumerable(Of Type)

returnValue = ReflectionUtil.GetAllBaseTypes()
```

**C++**<br />
``` C++
public:
generic<typename T>
static IEnumerable<Type^>^ GetAllBaseTypes()
```

**F#**<br />
``` F#
static member GetAllBaseTypes : unit -> IEnumerable<Type> 

```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The source Type.</dd></dl>

#### Return Value
Type: IEnumerable(Type)<br />The type from which the source Type directly inherits, and the types from which the inherited types inherits; or a null reference (`Nothing` in Visual Basic) if the source Type represents the Object class or an interface.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim types As IEnumerable(Of Type) = GetAllBaseTypes(Of Form)()

Dim sb As New StringBuilder()
sb.AppendLine($"Type inheritance hierarchy of '{GetType(Form).FullName}':")
sb.AppendLine()

For i As Integer = 0 To (types.Count - 1)
    sb.AppendLine($"{String.Concat(Enumerable.Repeat(" "c, (i * 4)))}{types(i).FullName}")
Next i

Console.WriteLine(sb.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />