# DiffLibUtil.DumpDiffRtf Method 
 

Builds a Rich-Text string with all the differences highlighted between two strings.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DiffLib">DevCase.ThirdParty.DiffLib</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string DumpDiffRtf(
	string str1,
	string str2,
	Color forecolorNoChange,
	Color forecolorAdded,
	Color forecolorDeleted,
	Color backColorNoChange,
	Color backColorAdded,
	Color backColorDeleted,
	float fontSize = 0f
)
```

**VB**<br />
``` VB
Public Shared Function DumpDiffRtf ( 
	str1 As String,
	str2 As String,
	forecolorNoChange As Color,
	forecolorAdded As Color,
	forecolorDeleted As Color,
	backColorNoChange As Color,
	backColorAdded As Color,
	backColorDeleted As Color,
	Optional fontSize As Single = 0F
) As String
```

**VB Usage**<br />
``` VB Usage
Dim str1 As String
Dim str2 As String
Dim forecolorNoChange As Color
Dim forecolorAdded As Color
Dim forecolorDeleted As Color
Dim backColorNoChange As Color
Dim backColorAdded As Color
Dim backColorDeleted As Color
Dim fontSize As Single
Dim returnValue As String

returnValue = DiffLibUtil.DumpDiffRtf(str1, 
	str2, forecolorNoChange, forecolorAdded, 
	forecolorDeleted, backColorNoChange, 
	backColorAdded, backColorDeleted, 
	fontSize)
```

**C++**<br />
``` C++
public:
static String^ DumpDiffRtf(
	String^ str1, 
	String^ str2, 
	Color forecolorNoChange, 
	Color forecolorAdded, 
	Color forecolorDeleted, 
	Color backColorNoChange, 
	Color backColorAdded, 
	Color backColorDeleted, 
	float fontSize = 0f
)
```

**F#**<br />
``` F#
static member DumpDiffRtf : 
        str1 : string * 
        str2 : string * 
        forecolorNoChange : Color * 
        forecolorAdded : Color * 
        forecolorDeleted : Color * 
        backColorNoChange : Color * 
        backColorAdded : Color * 
        backColorDeleted : Color * 
        ?fontSize : float32 
(* Defaults:
        let _fontSize = defaultArg fontSize 0f
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>str1</dt><dd>Type: System.String<br />The first string to compare.</dd><dt>str2</dt><dd>Type: System.String<br />The second string to compare.</dd><dt>forecolorNoChange</dt><dd>Type: System.Drawing.Color<br />The forecolor to use for a string that has any changes.</dd><dt>forecolorAdded</dt><dd>Type: System.Drawing.Color<br />The forecolor to use for a string that has been added.</dd><dt>forecolorDeleted</dt><dd>Type: System.Drawing.Color<br />The forecolor to use for a string that has been deleted.</dd><dt>backColorNoChange</dt><dd>Type: System.Drawing.Color<br />The backcolor to use for a string that has any changes.</dd><dt>backColorAdded</dt><dd>Type: System.Drawing.Color<br />The backcolor to use for a string that has been added.</dd><dt>backColorDeleted</dt><dd>Type: System.Drawing.Color<br />The backcolor to use for a string that has been deleted.</dd><dt>fontSize (Optional)</dt><dd>Type: System.Single<br />The font size. 

 Set this value to `0.0` to let the system decide the font size, which normally is `8.25`</dd></dl>

#### Return Value
Type: String<br />The resulting Rich-Text string.

## Examples
This is a code example. 
**VB**<br />
``` VB

```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DiffLib_DiffLibUtil">DiffLibUtil Class</a><br /><a href="N_DevCase_ThirdParty_DiffLib">DevCase.ThirdParty.DiffLib Namespace</a><br />