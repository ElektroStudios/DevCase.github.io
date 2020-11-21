# DelegateExtensions.Combine Method 
 

Concatenates the invocation lists of the source Delegate with another Delegate.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Delegate">DevCase.Core.Extensions.Delegate</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Delegate Combine(
	this Delegate source,
	Delegate target
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Combine ( 
	source As Delegate,
	target As Delegate
) As Delegate
```

**VB Usage**<br />
``` VB Usage
Dim source As [Delegate]
Dim target As [Delegate]
Dim returnValue As [Delegate]

returnValue = source.Combine(target)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Delegate^ Combine(
	Delegate^ source, 
	Delegate^ target
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Combine : 
        source : Delegate * 
        target : Delegate -> Delegate 

```


#### Parameters
&nbsp;<dl><dt>source</dt><dd>Type: System.Delegate<br />The source Delegate whose invocation list comes first.</dd><dt>target</dt><dd>Type: System.Delegate<br />The Delegate whose invocation list comes last.</dd></dl>

#### Return Value
Type: Delegate<br />A new delegate with an invocation list that concatenates the invocation lists of *source* and *target* in that order. 

 Returns *source* if *target* is a null reference (`Nothing` in Visual Basic), 

 returns *target* if *source* is a null reference, 

 and returns a null reference if both *source* and *target* are null references.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Delegate. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Delegate_DelegateExtensions">DelegateExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Delegate">DevCase.Core.Extensions.Delegate Namespace</a><br />