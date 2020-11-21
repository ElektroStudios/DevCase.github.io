# ConsoleProgressBar.BlockInactiveChar Property 
 

Gets the character used to draw an inactive progress bar block. 

 Default value is: "·"

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public char BlockInactiveChar { get; set; }
```

**VB**<br />
``` VB
Public Property BlockInactiveChar As Char
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As ConsoleProgressBar
Dim value As Char

value = instance.BlockInactiveChar

instance.BlockInactiveChar = value
```

**C++**<br />
``` C++
public:
property wchar_t BlockInactiveChar {
	wchar_t get ();
	void set (wchar_t value);
}
```

**F#**<br />
``` F#
member BlockInactiveChar : char with get, set

```


#### Property Value
Type: Char<br />The character used to draw an inactive progress bar block.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ConsoleProgressBar">ConsoleProgressBar Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />