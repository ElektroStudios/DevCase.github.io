# GuidExtensions.AsNumber Method 
 

Converts the specified Guid to a unique numeric value of 19 length.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Guid">DevCase.Core.Extensions.Guid</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static long AsNumber(
	this Guid guid
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function AsNumber ( 
	guid As Guid
) As Long
```

**VB Usage**<br />
``` VB Usage
Dim guid As Guid
Dim returnValue As Long

returnValue = guid.AsNumber()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static long long AsNumber(
	Guid guid
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AsNumber : 
        guid : Guid -> int64 

```


#### Parameters
&nbsp;<dl><dt>guid</dt><dd>Type: System.Guid<br />The source Guid.</dd></dl>

#### Return Value
Type: Int64<br />The resulting number.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Guid. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Guid_GuidExtensions">GuidExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Guid">DevCase.Core.Extensions.Guid Namespace</a><br />