# FormExtensions.GetEventHandlers Method 
 

Gets all the delegates associated to the specified event raised by the source Form.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IReadOnlyCollection<Delegate> GetEventHandlers(
	this Form form,
	string eventName
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetEventHandlers ( 
	form As Form,
	eventName As String
) As IReadOnlyCollection(Of Delegate)
```

**VB Usage**<br />
``` VB Usage
Dim form As Form
Dim eventName As String
Dim returnValue As IReadOnlyCollection(Of Delegate)

returnValue = form.GetEventHandlers(eventName)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IReadOnlyCollection<Delegate^>^ GetEventHandlers(
	Form^ form, 
	String^ eventName
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetEventHandlers : 
        form : Form * 
        eventName : string -> IReadOnlyCollection<Delegate> 

```


#### Parameters
&nbsp;<dl><dt>form</dt><dd>Type: System.Windows.Forms.Form<br />The source Form.</dd><dt>eventName</dt><dd>Type: System.String<br />The name of the event. 

 Note: the name is case-insensitive.</dd></dl>

#### Return Value
Type: IReadOnlyCollection(Delegate)<br />All the delegates associated to the specified event raised by the source Form; or an empty IReadOnlyCollection(T) if there are no delegates associated.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Form. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim ctrl As New Button()
AddHandler ctrl.Click, Sub() Console.WriteLine("Click!") 

Dim handlers As IReadOnlyCollection(Of [Delegate]) = GetEventHandlers(ctrl, NameOf(Button.Click))
For Each handler As [Delegate] In handlers
    Console.WriteLine($"Method Name: {handler.Method.Name}")
Next handler
```


## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1

    Private WithEvents TestUserControl1 As New TestUserControl()

    Private sub TestUserControl1_TestEvent(sender As Object, e As EventArgs) Handles TestUserControl1.TestEvent
    End sub

    Private Sub Form1_Load(sender As Object, e As EventArgs) Handles MyBase.Shown
        Dim handlers As IReadOnlyCollection(Of [Delegate]) = GetEventHandlers(Me.TestUserControl1, NameOf(TestUserControl.TestEvent))
        For Each handler As [Delegate] In handlers
            Console.WriteLine($"Method Name: {handler.Method.Name}")
        Next handler
    End Sub

End Class

Public Class TestUserControl : Inherits UserControl

    Public Event TestEvent As EventHandler(Of EventArgs)

End Class
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Form_FormExtensions">FormExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form Namespace</a><br />