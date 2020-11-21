# EnvironmentVariableUtil.CurrentVariables Property 
 

Gets a IEnumerable(T) collection with the Environment Variable of the specified environment user.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<VariableInfo> this[
	EnvironmentVariableTarget scope
] { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CurrentVariables ( 
	scope As EnvironmentVariableTarget
) As ReadOnlyCollection(Of VariableInfo)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim scope As EnvironmentVariableTarget
Dim value As ReadOnlyCollection(Of VariableInfo)

value = EnvironmentVariableUtil.CurrentVariables(scope)

```

**C++**<br />
``` C++
public:
static property ReadOnlyCollection<VariableInfo^>^ CurrentVariables[EnvironmentVariableTarget scope] {
	ReadOnlyCollection<VariableInfo^>^ get (EnvironmentVariableTarget scope);
}
```

**F#**<br />
``` F#
static member CurrentVariables : ReadOnlyCollection<VariableInfo> with get

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: System.EnvironmentVariableTarget<br /></dd></dl>

#### Property Value
Type: ReadOnlyCollection(<a href="T_DevCase_Core_Shell_VariableInfo">VariableInfo</a>)<br />A IEnumerable(T) collection with the Environment Variable.

## Examples
This is a code example. 
**VB**<br />
``` VB
For Each envVar As VariableInfo In EnvironmentVariables.CurrentVariables(EnvironmentVariableTarget.User)

    Console.WriteLine(String.Format("Name:{0}; Value:{1}", envVar.Name, envVar.Value))

Next envVar
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentVariableUtil">EnvironmentVariableUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />