# ConsoleProgressBar.AnimationSpeed Property 
 

Gets or sets the speed (framerate) of the animation secuence defined in <a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_Animation">Animation</a>. 

 Default value is: 125 milliseconds.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public TimeSpan AnimationSpeed { get; set; }
```

**VB**<br />
``` VB
Public Property AnimationSpeed As TimeSpan
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As ConsoleProgressBar
Dim value As TimeSpan

value = instance.AnimationSpeed

instance.AnimationSpeed = value
```

**C++**<br />
``` C++
public:
property TimeSpan AnimationSpeed {
	TimeSpan get ();
	void set (TimeSpan value);
}
```

**F#**<br />
``` F#
member AnimationSpeed : TimeSpan with get, set

```


#### Property Value
Type: TimeSpan<br />The speed (framerate) of the animation secuence defined in <a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_Animation">Animation</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ConsoleProgressBar">ConsoleProgressBar Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />