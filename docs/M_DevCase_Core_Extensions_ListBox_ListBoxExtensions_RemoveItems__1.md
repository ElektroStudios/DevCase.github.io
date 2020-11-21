# ListBoxExtensions.RemoveItems(*T*) Method 
 

Removes items of the specified Type in the source ListBox given a condition.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void RemoveItems<T>(
	this ListBox sender,
	Func<T, bool> predicate
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub RemoveItems(Of T) ( 
	sender As ListBox,
	predicate As Func(Of T, Boolean)
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As ListBox
Dim predicate As Func(Of T, Boolean)

sender.RemoveItems(predicate)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static void RemoveItems(
	ListBox^ sender, 
	Func<T, bool>^ predicate
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member RemoveItems : 
        sender : ListBox * 
        predicate : Func<'T, bool> -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.ListBox<br />The source ListBox.</dd><dt>predicate</dt><dd>Type: System.Func(*T*, Boolean)<br />A Func(T, TResult) function to test each element for a condition.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The <a href="N_DevCase_Core_Extensions_Type">DevCase.Core.Extensions.Type</a> of items to remove.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListBox. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
ListBox1.Items.AddRange({Color.Red, Color.Green, Color.Blue})

Dim predicate As Func(Of Color, Boolean) =
    Function(c As Color) As Boolean
        Select Case c

            Case Color.Green
                Return True

            Case Else
                Return False

        End Select
    End Function

ListBox1.RemoveItems(Of Color)(predicate)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox Namespace</a><br />