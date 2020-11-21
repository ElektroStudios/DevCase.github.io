# ConsoleProgressBar.Animation Property 
 

Gets or sets the characters used to draw the animation secuence at the very end of the progress bar. 

 Default value is: {"|"c, "|"c, "/"c, "/"c, "-"c, "-"c, "\"c, "\"c} ( that is: "||//--\\" )

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public char[] Animation { get; set; }
```

**VB**<br />
``` VB
Public Property Animation As Char()
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As ConsoleProgressBar
Dim value As Char()

value = instance.Animation

instance.Animation = value
```

**C++**<br />
``` C++
public:
property array<wchar_t>^ Animation {
	array<wchar_t>^ get ();
	void set (array<wchar_t>^ value);
}
```

**F#**<br />
``` F#
member Animation : char[] with get, set

```


#### Property Value
Type: Char[]<br />The characters used to draw the animation secuence at the very end of the progress bar.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ConsoleProgressBar">ConsoleProgressBar Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />