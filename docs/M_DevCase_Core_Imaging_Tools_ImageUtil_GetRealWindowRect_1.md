# ImageUtil.GetRealWindowRect Method (Form)
 

Gets the (non-client) Rectangle of a window. 

 This method supports a borderless `Windows 10` window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Rectangle GetRealWindowRect(
	Form form
)
```

**VB**<br />
``` VB
Public Shared Function GetRealWindowRect ( 
	form As Form
) As Rectangle
```

**VB Usage**<br />
``` VB Usage
Dim form As Form
Dim returnValue As Rectangle

returnValue = ImageUtil.GetRealWindowRect(form)
```

**C++**<br />
``` C++
public:
static Rectangle GetRealWindowRect(
	Form^ form
)
```

**F#**<br />
``` F#
static member GetRealWindowRect : 
        form : Form -> Rectangle 

```


#### Parameters
&nbsp;<dl><dt>form</dt><dd>Type: System.Windows.Forms.Form<br />The Form.</dd></dl>

#### Return Value
Type: Rectangle<br />The resulting (non-client) Rectangle of the window.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ImageUtil_GetRealWindowRect">GetRealWindowRect Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />