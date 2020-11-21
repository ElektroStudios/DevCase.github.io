# TweakingUtil.DoubleClickSize Property 
 

Gets or sets the width and height, in pixels, of the double-click rectangle which the second click of a double-click must fall for it to be registered as a double-click.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Size DoubleClickSize { get; set; }
```

**VB**<br />
``` VB
Public Shared Property DoubleClickSize As Size
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Size

value = TweakingUtil.DoubleClickSize

TweakingUtil.DoubleClickSize = value
```

**C++**<br />
``` C++
public:
static property Size DoubleClickSize {
	Size get ();
	void set (Size value);
}
```

**F#**<br />
``` F#
static member DoubleClickSize : Size with get, set

```


#### Property Value
Type: Size<br />The width and height, in pixels, of the double-click rectangle which the second click of a double-click must fall for it to be registered as a double-click.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr><tr><td>ArgumentException</td><td>Width should be greater than 31.;value</td></tr><tr><td>ArgumentException</td><td>Height should be greater than 31.;value</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />