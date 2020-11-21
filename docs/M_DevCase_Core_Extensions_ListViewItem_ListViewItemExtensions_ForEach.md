# ListViewItemExtensions.ForEach Method 
 

Performs the specified action on each item of the specified ListViewItem array.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListViewItem">DevCase.Core.Extensions.ListViewItem</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ForEach(
	this ListViewItem[] items,
	Action<ListViewItem> action
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Sub ForEach ( 
	items As ListViewItem(),
	action As Action(Of ListViewItem)
)
```

**VB Usage**<br />
``` VB Usage
Dim items As ListViewItem()
Dim action As Action(Of ListViewItem)

items.ForEach(action)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static void ForEach(
	array<ListViewItem^>^ items, 
	Action<ListViewItem^>^ action
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member ForEach : 
        items : ListViewItem[] * 
        action : Action<ListViewItem> -> unit 

```


#### Parameters
&nbsp;<dl><dt>items</dt><dd>Type: System.Windows.Forms.ListViewItem[]<br />The source ListViewItem array.</dd><dt>action</dt><dd>Type: System.Action(ListViewItem)<br />The action to perform on each item of the source array.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListViewItem_ListViewItemExtensions">ListViewItemExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_ListViewItem">DevCase.Core.Extensions.ListViewItem Namespace</a><br />