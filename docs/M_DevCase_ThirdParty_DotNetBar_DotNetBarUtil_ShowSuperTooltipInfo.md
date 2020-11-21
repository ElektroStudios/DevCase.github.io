# DotNetBarUtil.ShowSuperTooltipInfo Method 
 

Shows a SuperTooltipInfo at the specified location.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetBar">DevCase.ThirdParty.DotNetBar</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ShowSuperTooltipInfo(
	SuperTooltip superToolTip,
	string headerText = "",
	string bodyText = "",
	Image bodyImage = null,
	string footerText = "",
	Image footerImage = null,
	eTooltipColor backColor = eTooltipColor.System,
	Point location = null,
	int duration = 2,
	bool positionBelowControl = false
)
```

**VB**<br />
``` VB
Public Shared Sub ShowSuperTooltipInfo ( 
	superToolTip As SuperTooltip,
	Optional headerText As String = "",
	Optional bodyText As String = "",
	Optional bodyImage As Image = Nothing,
	Optional footerText As String = "",
	Optional footerImage As Image = Nothing,
	Optional backColor As eTooltipColor = eTooltipColor.System,
	Optional location As Point = Nothing,
	Optional duration As Integer = 2,
	Optional positionBelowControl As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim superToolTip As SuperTooltip
Dim headerText As String
Dim bodyText As String
Dim bodyImage As Image
Dim footerText As String
Dim footerImage As Image
Dim backColor As eTooltipColor
Dim location As Point
Dim duration As Integer
Dim positionBelowControl As BooleanDotNetBarUtil.ShowSuperTooltipInfo(superToolTip, 
	headerText, bodyText, bodyImage, 
	footerText, footerImage, backColor, 
	location, duration, positionBelowControl)
```

**C++**<br />
``` C++
public:
static void ShowSuperTooltipInfo(
	SuperTooltip^ superToolTip, 
	String^ headerText = L"", 
	String^ bodyText = L"", 
	Image^ bodyImage = nullptr, 
	String^ footerText = L"", 
	Image^ footerImage = nullptr, 
	eTooltipColor backColor = eTooltipColor::System, 
	Point location = nullptr, 
	int duration = 2, 
	bool positionBelowControl = false
)
```

**F#**<br />
``` F#
static member ShowSuperTooltipInfo : 
        superToolTip : SuperTooltip * 
        ?headerText : string * 
        ?bodyText : string * 
        ?bodyImage : Image * 
        ?footerText : string * 
        ?footerImage : Image * 
        ?backColor : eTooltipColor * 
        ?location : Point * 
        ?duration : int * 
        ?positionBelowControl : bool 
(* Defaults:
        let _headerText = defaultArg headerText ""
        let _bodyText = defaultArg bodyText ""
        let _bodyImage = defaultArg bodyImage null
        let _footerText = defaultArg footerText ""
        let _footerImage = defaultArg footerImage null
        let _backColor = defaultArg backColor eTooltipColor.System
        let _location = defaultArg location null
        let _duration = defaultArg duration 2
        let _positionBelowControl = defaultArg positionBelowControl false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>superToolTip</dt><dd>Type: SuperTooltip<br />The SuperTooltip control.</dd><dt>headerText (Optional)</dt><dd>Type: System.String<br />The header text.</dd><dt>bodyText (Optional)</dt><dd>Type: System.String<br />The body text.</dd><dt>bodyImage (Optional)</dt><dd>Type: System.Drawing.Image<br />The body image.</dd><dt>footerText (Optional)</dt><dd>Type: System.String<br />The footer text.</dd><dt>footerImage (Optional)</dt><dd>Type: System.Drawing.Image<br />The footer image.</dd><dt>backColor (Optional)</dt><dd>Type: eTooltipColor<br />The SuperTooltip background color.</dd><dt>location (Optional)</dt><dd>Type: System.Drawing.Point<br />The location where to show the SuperTooltip.</dd><dt>duration (Optional)</dt><dd>Type: System.Int32<br />The SuperTooltip duration.</dd><dt>positionBelowControl (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), the SuperTooltip is shown below the control.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim superTooltip1 As New SuperTooltip

ShowSuperTooltipInfo(superTooltip1,
                     "I'm the Header", "I'm the Body", , "I'm the Footer", ,
                     eTooltipColor.Blue, MousePosition, 2, False)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetBar_DotNetBarUtil">DotNetBarUtil Class</a><br /><a href="N_DevCase_ThirdParty_DotNetBar">DevCase.ThirdParty.DotNetBar Namespace</a><br />