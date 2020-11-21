# IconLibUtil.GetIconLayers Method 
 

Gets the image layers contained inside a icon file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_IconLib">DevCase.ThirdParty.IconLib</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static SingleIcon GetIconLayers(
	string iconfile
)
```

**VB**<br />
``` VB
Public Shared Function GetIconLayers ( 
	iconfile As String
) As SingleIcon
```

**VB Usage**<br />
``` VB Usage
Dim iconfile As String
Dim returnValue As SingleIcon

returnValue = IconLibUtil.GetIconLayers(iconfile)
```

**C++**<br />
``` C++
public:
static SingleIcon^ GetIconLayers(
	String^ iconfile
)
```

**F#**<br />
``` F#
static member GetIconLayers : 
        iconfile : string -> SingleIcon 

```


#### Parameters
&nbsp;<dl><dt>iconfile</dt><dd>Type: System.String<br />The source icon filepath.</dd></dl>

#### Return Value
Type: SingleIcon<br />The resulting SingleIcon.

## Examples
This is a code example. 
**VB**<br />
``` VB
For Each iconLayer As IconLib.IconImage In GetIconLayers("C:\Image.ico")
    PictureBox1.BackgroundImage = iconLayer.Icon.ToBitmap()
    Debug.WriteLine(iconLayer.Icon.Size.ToString())
    Application.DoEvents()
    Threading.Thread.Sleep(750)
Next iconLayer
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_IconLib_IconLibUtil">IconLibUtil Class</a><br /><a href="N_DevCase_ThirdParty_IconLib">DevCase.ThirdParty.IconLib Namespace</a><br />