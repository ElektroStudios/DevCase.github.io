# MutexExtensions.GetOwnerThreadId Method 
 

Gets the thread identifier of the process that owns the source Mutex.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Mutex">DevCase.Core.Extensions.Mutex</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int GetOwnerThreadId(
	this Mutex sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetOwnerThreadId ( 
	sender As Mutex
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim sender As Mutex
Dim returnValue As Integer

returnValue = sender.GetOwnerThreadId()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static int GetOwnerThreadId(
	Mutex^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetOwnerThreadId : 
        sender : Mutex -> int 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Threading.Mutex<br />The source Mutex.</dd></dl>

#### Return Value
Type: Int32<br />The thread identifier of the process that owns the source Mutex

 If the mutex is abandoned, the return value is zero.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Mutex. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mutexName As String = String.Format("Global\{{{0}}}", New Guid().ToString())
Dim mutex As New Mutex(initiallyOwned:=True, name:=mutexName)
Dim threadId As Integer = mutex.GetOwnerThreadId()
Console.WriteLine(threadId)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Mutex_MutexExtensions">MutexExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Mutex">DevCase.Core.Extensions.Mutex Namespace</a><br />