# TreeViewExtensions.RestoreTreeState Method 
 

Restores a state of the source TreeView previously saved using the <a href="M_DevCase_Core_Extensions_TreeView_TreeViewExtensions_SaveTreeState">SaveTreeState(TreeView)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_TreeView">DevCase.Core.Extensions.TreeView</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void RestoreTreeState(
	this TreeView sender,
	Dictionary<int, bool> saveState
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub RestoreTreeState ( 
	sender As TreeView,
	saveState As Dictionary(Of Integer, Boolean)
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As TreeView
Dim saveState As Dictionary(Of Integer, Boolean)

sender.RestoreTreeState(saveState)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void RestoreTreeState(
	TreeView^ sender, 
	Dictionary<int, bool>^ saveState
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member RestoreTreeState : 
        sender : TreeView * 
        saveState : Dictionary<int, bool> -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.TreeView<br />The source TreeView.</dd><dt>saveState</dt><dd>Type: System.Collections.Generic.Dictionary(Int32, Boolean)<br />A Dictionary(TKey, TValue) containing the hash code of each node and its expansion state.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type TreeView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim saveState As Dictionary(Of Integer, Boolean)

Private Sub Button_SaveTreeState(sender As Object, e As EventArgs) Handles Button_SaveTreeState.Click
    saveState = Me.TreeView1.SaveTreeState()
End Sub

Private Sub Button_RestoreTreeState(sender As Object, e As EventArgs) Handles Button_RestoreTreeState.Click
    Me.TreeView1.RestoreTreeState(saveState)
End Sub
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_TreeView_TreeViewExtensions">TreeViewExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_TreeView">DevCase.Core.Extensions.TreeView Namespace</a><br />