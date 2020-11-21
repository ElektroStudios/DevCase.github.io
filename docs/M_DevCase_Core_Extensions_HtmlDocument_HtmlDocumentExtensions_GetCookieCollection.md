# HtmlDocumentExtensions.GetCookieCollection Method 
 

Gets a CookieCollection containing the stored cookies in the source Document.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_HtmlDocument">DevCase.Core.Extensions.HtmlDocument</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static CookieCollection GetCookieCollection(
	this HtmlDocument sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetCookieCollection ( 
	sender As HtmlDocument
) As CookieCollection
```

**VB Usage**<br />
``` VB Usage
Dim sender As HtmlDocument
Dim returnValue As CookieCollection

returnValue = sender.GetCookieCollection()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static CookieCollection^ GetCookieCollection(
	HtmlDocument^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetCookieCollection : 
        sender : HtmlDocument -> CookieCollection 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.HtmlDocument<br />The source HtmlDocument.</dd></dl>

#### Return Value
Type: CookieCollection<br />The resulting CookieCollection.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type HtmlDocument. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1

    Private uri As New Uri("https://foro.elhacker.net/")

    Private Sub Form1_Shown(sender As Object, e As System.Eventing) Handles MyBase.Shown
        Me.WebBrowser1.ScriptErrorsSuppressed = True
        Me.WebBrowser1.Navigate(uri)
    End Sub

    Private Sub WebBrowser1_DocumentCompleted(sender As Object, e As WebBrowserDocumentCompletedEventArgs) Handles WebBrowser1.DocumentCompleted

        Dim wb As WebBrowser = DirectCast(sender, WebBrowser)

        If Not (wb.ReadyState = WebBrowserReadyState.Complete) OrElse Not (e.Url = Me.uri) Then
            Exit Sub
        End If

        Dim cookies As CookieCollection = GetCookieCollection(wb.Document)
        For Each cookie As Cookie In cookies
            Console.WriteLine(cookie.ToString())
        Next cookie

    End Sub

End Class
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_HtmlDocument_HtmlDocumentExtensions">HtmlDocumentExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_HtmlDocument">DevCase.Core.Extensions.HtmlDocument Namespace</a><br />