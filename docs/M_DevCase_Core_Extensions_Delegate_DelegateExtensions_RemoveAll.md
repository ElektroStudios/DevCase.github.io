# DelegateExtensions.RemoveAll Method 
 

Removes all occurrences of the invocation list of the source Delegate from the invocation list of another Delegate.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Delegate">DevCase.Core.Extensions.Delegate</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Delegate RemoveAll(
	this Delegate source,
	Delegate target
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function RemoveAll ( 
	source As Delegate,
	target As Delegate
) As Delegate
```

**VB Usage**<br />
``` VB Usage
Dim source As [Delegate]
Dim target As [Delegate]
Dim returnValue As [Delegate]

returnValue = source.RemoveAll(target)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Delegate^ RemoveAll(
	Delegate^ source, 
	Delegate^ target
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member RemoveAll : 
        source : Delegate * 
        target : Delegate -> Delegate 

```


#### Parameters
&nbsp;<dl><dt>source</dt><dd>Type: System.Delegate<br />The source Delegate from which to remove the invocation list of.</dd><dt>target</dt><dd>Type: System.Delegate<br />The Delegate that supplies the invocation list to remove from the invocation list of.</dd></dl>

#### Return Value
Type: Delegate<br />A new delegate with an invocation list formed by taking the invocation list of *source* and removing all occurrences of the invocation list of *target*, if the invocation list of value is found within the invocation list of source. 

 Returns *source* if value is a null reference (`Nothing` in Visual Basic) or if the invocation list of *target* is not found within the invocation list of *source*. 

 Returns a null reference if the invocation list of *target* is equal to the invocation list of *source*, if *source* contains only a series of invocation lists that are equal to the invocation list of *source*, or if *source* is a null reference.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Delegate. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Delegate_DelegateExtensions">DelegateExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Delegate">DevCase.Core.Extensions.Delegate Namespace</a><br />