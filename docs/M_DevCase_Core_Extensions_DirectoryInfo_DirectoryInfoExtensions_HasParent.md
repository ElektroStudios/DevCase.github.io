# DirectoryInfoExtensions.HasParent Method 
 

Determines whether the directory has a parent directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool HasParent(
	this DirectoryInfo sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function HasParent ( 
	sender As DirectoryInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As DirectoryInfo
Dim returnValue As Boolean

returnValue = sender.HasParent()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool HasParent(
	DirectoryInfo^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member HasParent : 
        sender : DirectoryInfo -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.DirectoryInfo<br />The source DirectoryInfo.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the directory has a parent directory, otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DirectoryInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions">DirectoryInfoExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo Namespace</a><br />