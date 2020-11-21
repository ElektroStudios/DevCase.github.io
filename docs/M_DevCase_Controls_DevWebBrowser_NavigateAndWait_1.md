# DevWebBrowser.NavigateAndWait Method (String, Boolean)
 

Navigates to the specified url and waits the page to be loaded.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public void NavigateAndWait(
	string url,
	bool newWindow
)
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Sub NavigateAndWait ( 
	url As String,
	newWindow As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevWebBrowser
Dim url As String
Dim newWindow As Boolean

instance.NavigateAndWait(url, newWindow)
```

**C++**<br />
``` C++
public:
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
void NavigateAndWait(
	String^ url, 
	bool newWindow
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member NavigateAndWait : 
        url : string * 
        newWindow : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The url to navigate.</dd><dt>newWindow</dt><dd>Type: System.Boolean<br />Indicates whether the url should be open into a new browser window.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Controls_DevWebBrowser">DevWebBrowser Class</a><br /><a href="Overload_DevCase_Controls_DevWebBrowser_NavigateAndWait">NavigateAndWait Overload</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />