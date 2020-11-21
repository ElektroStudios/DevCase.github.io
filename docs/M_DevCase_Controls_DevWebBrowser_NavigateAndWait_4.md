# DevWebBrowser.NavigateAndWait Method (Uri)
 

Navigates to the specified url and waits the page to be loaded.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public void NavigateAndWait(
	Uri uri
)
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Sub NavigateAndWait ( 
	uri As Uri
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevWebBrowser
Dim uri As Uri

instance.NavigateAndWait(uri)
```

**C++**<br />
``` C++
public:
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
void NavigateAndWait(
	Uri^ uri
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member NavigateAndWait : 
        uri : Uri -> unit 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />The url to navigate.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Controls_DevWebBrowser">DevWebBrowser Class</a><br /><a href="Overload_DevCase_Controls_DevWebBrowser_NavigateAndWait">NavigateAndWait Overload</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />