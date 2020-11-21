# ThemeInfo Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Shell_ThemeInfo">ThemeInfo</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ThemeInfo(
	string filepath,
	string colorSchemeName,
	string sizeName
)
```

**VB**<br />
``` VB
Public Sub New ( 
	filepath As String,
	colorSchemeName As String,
	sizeName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim colorSchemeName As String
Dim sizeName As String

Dim instance As New ThemeInfo(filepath, 
	colorSchemeName, sizeName)
```

**C++**<br />
``` C++
public:
ThemeInfo(
	String^ filepath, 
	String^ colorSchemeName, 
	String^ sizeName
)
```

**F#**<br />
``` F#
new : 
        filepath : string * 
        colorSchemeName : string * 
        sizeName : string -> ThemeInfo
```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The theme filepath.</dd><dt>colorSchemeName</dt><dd>Type: System.String<br />The theme color scheme name.</dd><dt>sizeName</dt><dd>Type: System.String<br />The theme size name.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>filepath or colorSchemeName or sizeName</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_ThemeInfo">ThemeInfo Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />