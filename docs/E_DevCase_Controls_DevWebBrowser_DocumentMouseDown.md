# DevWebBrowser.DocumentMouseDown Event
 

Occurs when the user clicks a mouse button on the current html document.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public event EventHandler<HtmlElementEventArgs> DocumentMouseDown
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Event DocumentMouseDown As EventHandler(Of HtmlElementEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevWebBrowser
Dim handler As EventHandler(Of HtmlElementEventArgs)

AddHandler instance.DocumentMouseDown, handler

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
 event EventHandler<HtmlElementEventArgs^>^ DocumentMouseDown {
	void add (EventHandler<HtmlElementEventArgs^>^ value);
	void remove (EventHandler<HtmlElementEventArgs^>^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member DocumentMouseDown : IEvent<EventHandler<HtmlElementEventArgs>,
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

    Private Sub ElektroWebBrowser1_DocumentMouseDown(ByVal sender As Object, ByVal e As HtmlElementEventArgs) Handles ElektroWebBrowser1.DocumentMouseDown

        Dim wb As DevWebBrowser = DirectCast(sender, ElektroWebBrowser)

        Select Case e.MouseButtonsPressed

            Case MouseButtons.Left

                Dim element As HtmlElement = wb.Document.GetElementFromPoint(e.ClientMousePosition)
                If (element IsNot Nothing) Then
                    Dim url As String = element.GetAttribute("href")
                    If Not String.IsNullOrWhiteSpace(url) Then
                        Dim uri As Uri = Nothing
                        If (Uri.TryCreate(url, UriKind.RelativeOrAbsolute, uri)) Then
                            wb.AllowNavigation = False
                            ' Here goes your code...
                            Console.WriteLine(uri.ToString())
                        End If ' uri
                    End If ' url
                End If ' element

            Case Else
                wb.AllowNavigation = True

        End Select

    End Sub

End Class
```


## See Also


#### Reference
<a href="T_DevCase_Controls_DevWebBrowser">DevWebBrowser Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />