# SizeFExtensions.Intersect Method 
 

Intersects two SizeF.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_SizeF">DevCase.Core.Extensions.SizeF</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static SizeF Intersect(
	this SizeF sender,
	SizeF second
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Intersect ( 
	sender As SizeF,
	second As SizeF
) As SizeF
```

**VB Usage**<br />
``` VB Usage
Dim sender As SizeF
Dim second As SizeF
Dim returnValue As SizeF

returnValue = sender.Intersect(second)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static SizeF Intersect(
	SizeF sender, 
	SizeF second
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Intersect : 
        sender : SizeF * 
        second : SizeF -> SizeF 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.SizeF<br />The first SizeF to intersect.</dd><dt>second</dt><dd>Type: System.Drawing.SizeF<br />The second SizeF to intersect.</dd></dl>

#### Return Value
Type: SizeF<br />The resulting SizeF.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type SizeF. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_SizeF_SizeFExtensions">SizeFExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_SizeF">DevCase.Core.Extensions.SizeF Namespace</a><br />