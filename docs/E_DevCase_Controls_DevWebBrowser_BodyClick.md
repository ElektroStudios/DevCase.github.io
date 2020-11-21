# DevWebBrowser.BodyClick Event
 

Occurs when the user clicks a mouse button on the current html body.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public event EventHandler<HtmlElementEventArgs> BodyClick
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Event BodyClick As EventHandler(Of HtmlElementEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevWebBrowser
Dim handler As EventHandler(Of HtmlElementEventArgs)

AddHandler instance.BodyClick, handler

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
 event EventHandler<HtmlElementEventArgs^>^ BodyClick {
	void add (EventHandler<HtmlElementEventArgs^>^ value);
	void remove (EventHandler<HtmlElementEventArgs^>^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member BodyClick : IEvent<EventHandler<HtmlElementEventArgs>,
    HtmlElementEventArgs>

```


#### Value
Type: System.EventHandler(HtmlElementEventArgs)

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1

    Private Sub Form1_Shown(ByVal sender As Object, ByVal e As EventArgs) Handles MyBase.Shown
        Me.ElektroWebBrowser1.Navigate("http://foro.elhacker.net/")
    End Sub

    Private Sub ElektroWebBrowser1_BodyClick(ByVal sender As Object, ByVal e As HtmlElementEventArgs) Handles ElektroWebBrowser1.BodyClick

        Dim wb As DevWebBrowser = DirectCast(sender, ElektroWebBrowser)

        Select Case e.MouseButtonsPressed
            ' Here goes your code...
        End Select

    End Sub

End Class
```


## See Also


#### Reference
<a href="T_DevCase_Controls_DevWebBrowser">DevWebBrowser Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />