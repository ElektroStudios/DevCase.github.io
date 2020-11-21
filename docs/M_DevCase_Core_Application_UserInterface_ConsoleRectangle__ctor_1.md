# ConsoleRectangle Constructor (Point, Size, Char, Char, Char, Char)
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a> structure.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ConsoleRectangle(
	Point location,
	Size size,
	char charLeft,
	char charTop,
	char charRight,
	char charBottom
)
```

**VB**<br />
``` VB
Public Sub New ( 
	location As Point,
	size As Size,
	charLeft As Char,
	charTop As Char,
	charRight As Char,
	charBottom As Char
)
```

**VB Usage**<br />
``` VB Usage
Dim location As Point
Dim size As Size
Dim charLeft As Char
Dim charTop As Char
Dim charRight As Char
Dim charBottom As Char

Dim instance As New ConsoleRectangle(location, 
	size, charLeft, charTop, charRight, 
	charBottom)
```

**C++**<br />
``` C++
public:
ConsoleRectangle(
	Point location, 
	Size size, 
	wchar_t charLeft, 
	wchar_t charTop, 
	wchar_t charRight, 
	wchar_t charBottom
)
```

**F#**<br />
``` F#
new : 
        location : Point * 
        size : Size * 
        charLeft : char * 
        charTop : char * 
        charRight : char * 
        charBottom : char -> ConsoleRectangle
```


#### Parameters
&nbsp;<dl><dt>location</dt><dd>Type: System.Drawing.Point<br />The location for this <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a> on a console output buffer.</dd><dt>size</dt><dd>Type: System.Drawing.Size<br />The size for this <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a>.</dd><dt>charLeft</dt><dd>Type: System.Char<br />The character to print the left border of this <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a> on a console output buffer.</dd><dt>charTop</dt><dd>Type: System.Char<br />The character to print the top border of this <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a> on a console output buffer.</dd><dt>charRight</dt><dd>Type: System.Char<br />The character to print the right border of this <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a> on a console output buffer.</dd><dt>charBottom</dt><dd>Type: System.Char<br />The character to print the bottom border of this <a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle</a> on a console output buffer.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ConsoleRectangle">ConsoleRectangle Structure</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_ConsoleRectangle__ctor">ConsoleRectangle Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />