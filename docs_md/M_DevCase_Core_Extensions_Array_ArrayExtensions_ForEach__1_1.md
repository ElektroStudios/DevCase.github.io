# ArrayExtensions.ForEach(*T*) Method (*T*[,], Action(*T*))
 

Performs the specified action on each element of the specified three-dimensional array.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void ForEach<T>(
	this T[,,] array,
	Action<T> action
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub ForEach(Of T) ( 
	array As T(,,),
	action As Action(Of T)
)
```

**VB Usage**<br />
``` VB Usage
Dim array As T(,,)
Dim action As Action(Of T)

array.ForEach(action)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static void ForEach(
	array<T,3>^ array, 
	Action<T>^ action
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ForEach : 
        array : 'T[,,] * 
        action : Action<'T> -> unit 

```


#### Parameters
&nbsp;<dl><dt>array</dt><dd>Type: *T*[,]<br />The source three-dimensional array.</dd><dt>action</dt><dd>Type: System.Action(*T*)<br />The Action to perform on each element of the three-dimensional array.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the object to find.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Array_ArrayExtensions">ArrayExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Array_ArrayExtensions_ForEach">ForEach Overload</a><br /><a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array Namespace</a><br />