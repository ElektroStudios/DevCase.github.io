# IconLibUtil.CreateIcon Method 
 

Creates a icon object from the specified image file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_IconLib">DevCase.ThirdParty.IconLib</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static SingleIcon CreateIcon(
	string filepath,
	IconOutputFormat format = IconOutputFormat.All
)
```

**VB**<br />
``` VB
Public Shared Function CreateIcon ( 
	filepath As String,
	Optional format As IconOutputFormat = IconOutputFormat.All
) As SingleIcon
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim format As IconOutputFormat
Dim returnValue As SingleIcon

returnValue = IconLibUtil.CreateIcon(filepath, 
	format)
```

**C++**<br />
``` C++
public:
static SingleIcon^ CreateIcon(
	String^ filepath, 
	IconOutputFormat format = IconOutputFormat::All
)
```

**F#**<br />
``` F#
static member CreateIcon : 
        filepath : string * 
        ?format : IconOutputFormat 
(* Defaults:
        let _format = defaultArg format IconOutputFormat.All
*)
-> SingleIcon 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The source image filepath.</dd><dt>format (Optional)</dt><dd>Type: IconOutputFormat<br />The icon format.</dd></dl>

#### Return Value
Type: SingleIcon<br />The resulting SingleIcon.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim iconFile As IconLib.SingleIcon = CreateIcon("C:\Image.ico", IconLib.IconOutputFormat.All)
For Each iconLayer As IconLib.IconImage In iconFile
    PictureBox1.BackgroundImage = iconLayer.Icon.ToBitmap()
    Debug.WriteLine(iconLayer.Icon.Size.ToString())
    Application.DoEvents()
    Threading.Thread.Sleep(750)
Next iconLayer
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_IconLib_IconLibUtil">IconLibUtil Class</a><br /><a href="N_DevCase_ThirdParty_IconLib">DevCase.ThirdParty.IconLib Namespace</a><br />