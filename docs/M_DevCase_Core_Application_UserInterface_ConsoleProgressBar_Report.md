# ConsoleProgressBar.Report Method 
 

Reports a progress update.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Report(
	double value
)
```

**VB**<br />
``` VB
Public Sub Report ( 
	value As Double
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ConsoleProgressBar
Dim value As Double

instance.Report(value)
```

**C++**<br />
``` C++
public:
virtual void Report(
	double value
) sealed
```

**F#**<br />
``` F#
abstract Report : 
        value : float -> unit 
override Report : 
        value : float -> unit 
```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.Double<br />The value of the updated progress.</dd></dl>

#### Implements
IProgress(T).Report(T)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ConsoleProgressBar">ConsoleProgressBar Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />