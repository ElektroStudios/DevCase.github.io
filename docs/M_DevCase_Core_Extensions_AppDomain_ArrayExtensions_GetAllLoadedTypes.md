# ArrayExtensions.GetAllLoadedTypes Method 
 

Gets all the loaded types in the source AppDomain.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_AppDomain">DevCase.Core.Extensions.AppDomain</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<Type> GetAllLoadedTypes(
	this AppDomain domain
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetAllLoadedTypes ( 
	domain As AppDomain
) As IEnumerable(Of Type)
```

**VB Usage**<br />
``` VB Usage
Dim domain As AppDomain
Dim returnValue As IEnumerable(Of Type)

returnValue = domain.GetAllLoadedTypes()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IEnumerable<Type^>^ GetAllLoadedTypes(
	AppDomain^ domain
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetAllLoadedTypes : 
        domain : AppDomain -> IEnumerable<Type> 

```


#### Parameters
&nbsp;<dl><dt>domain</dt><dd>Type: System.AppDomain<br />The source AppDomain.</dd></dl>

#### Return Value
Type: IEnumerable(Type)<br />Returns all the loaded types in the source AppDomain.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type AppDomain. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_AppDomain_ArrayExtensions">ArrayExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_AppDomain">DevCase.Core.Extensions.AppDomain Namespace</a><br />