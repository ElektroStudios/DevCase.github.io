# WebBrowserExtensions.GetCookieContainer Method 
 

Gets a CookieContainer containing the stored cookies for the active website in the source WebBrowser. (that is, the active opened document in the Document property).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_WebBrowser">DevCase.Core.Extensions.WebBrowser</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static CookieContainer GetCookieContainer(
	this WebBrowser wb
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetCookieContainer ( 
	wb As WebBrowser
) As CookieContainer
```

**VB Usage**<br />
``` VB Usage
Dim wb As WebBrowser
Dim returnValue As CookieContainer

returnValue = wb.GetCookieContainer()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static CookieContainer^ GetCookieContainer(
	WebBrowser^ wb
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetCookieContainer : 
        wb : WebBrowser -> CookieContainer 

```


#### Parameters
&nbsp;<dl><dt>wb</dt><dd>Type: System.Windows.Forms.WebBrowser<br />The source WebBrowser.</dd></dl>

#### Return Value
Type: CookieContainer<br />The resulting CookieContainer.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type WebBrowser. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

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

        Dim cookies As CookieContainer = GetCookieContainer(wb)
        For Each cookie As Cookie In cookies.GetCookies(Me.uri)
            Console.WriteLine(cookie.ToString())
        Next cookie

    End Sub

End Class
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_WebBrowser_WebBrowserExtensions">WebBrowserExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_WebBrowser">DevCase.Core.Extensions.WebBrowser Namespace</a><br />