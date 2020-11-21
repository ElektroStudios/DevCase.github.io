# ArrayExtensions.InitializeAll(*T*) Method (*T*[][])
 

Initializes all the elements (that aren't already initialized) of the specified jagged Array.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void InitializeAll<T>(
	this T[][] sender
)
where T : new()

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub InitializeAll(Of T As New) ( 
	sender As T()()
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As T()()

sender.InitializeAll()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
where T : gcnew()
static void InitializeAll(
	array<array<T>^>^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member InitializeAll : 
        sender : 'T[][] -> unit  when 'T : new()

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: *T*[][]<br />The source jagged Array.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Array_ArrayExtensions">ArrayExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Array_ArrayExtensions_InitializeAll">InitializeAll Overload</a><br /><a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array Namespace</a><br />