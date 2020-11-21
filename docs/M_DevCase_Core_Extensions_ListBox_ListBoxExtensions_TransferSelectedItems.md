# ListBoxExtensions.TransferSelectedItems Method 
 

Transfers the selected items from the source ListBox to another.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void TransferSelectedItems(
	this ListBox src,
	ListBox dst
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub TransferSelectedItems ( 
	src As ListBox,
	dst As ListBox
)
```

**VB Usage**<br />
``` VB Usage
Dim src As ListBox
Dim dst As ListBox

src.TransferSelectedItems(dst)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void TransferSelectedItems(
	ListBox^ src, 
	ListBox^ dst
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member TransferSelectedItems : 
        src : ListBox * 
        dst : ListBox -> unit 

```


#### Parameters
&nbsp;<dl><dt>src</dt><dd>Type: System.Windows.Forms.ListBox<br />The source ListBox.</dd><dt>dst</dt><dd>Type: System.Windows.Forms.ListBox<br />The destination ListBox.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListBox. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox Namespace</a><br />