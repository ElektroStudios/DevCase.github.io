# ThreadExtensions.JoinAll Method (IEnumerable(Thread))
 

Blocks the calling thread until the specified threads terminates, while continuing to perform standard COM and SendMessage pumping.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Thread">DevCase.Core.Extensions.Thread</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void JoinAll(
	this IEnumerable<Thread> threads
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub JoinAll ( 
	threads As IEnumerable(Of Thread)
)
```

**VB Usage**<br />
``` VB Usage
Dim threads As IEnumerable(Of Thread)

threads.JoinAll()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void JoinAll(
	IEnumerable<Thread^>^ threads
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member JoinAll : 
        threads : IEnumerable<Thread> -> unit 

```


#### Parameters
&nbsp;<dl><dt>threads</dt><dd>Type: System.Collections.Generic.IEnumerable(Thread)<br />The threads.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(Thread). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Thread_ThreadExtensions">ThreadExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Thread_ThreadExtensions_JoinAll">JoinAll Overload</a><br /><a href="N_DevCase_Core_Extensions_Thread">DevCase.Core.Extensions.Thread Namespace</a><br />