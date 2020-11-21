# MutexExtensions.IsAbandoned Method 
 

Determines whether the source Mutex is abandoned. 

 If a thread terminates while owning a mutex, the mutex is said to be "abandoned". The state of the mutex is set to signaled, and the next waiting thread gets ownership.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Mutex">DevCase.Core.Extensions.Mutex</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsAbandoned(
	this Mutex sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsAbandoned ( 
	sender As Mutex
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As Mutex
Dim returnValue As Boolean

returnValue = sender.IsAbandoned()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsAbandoned(
	Mutex^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsAbandoned : 
        sender : Mutex -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Threading.Mutex<br />The source Mutex.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the source Mutex is abandoned; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Mutex. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mutexName As String = String.Format("Global\{{{0}}}", New Guid().ToString())
Dim mutex As New Mutex(initiallyOwned:=False, name:=mutexName)
Dim isAbandoned As Boolean = mutex.IsAbandoned()
Console.WriteLine(isAbandoned)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Mutex_MutexExtensions">MutexExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Mutex">DevCase.Core.Extensions.Mutex Namespace</a><br />