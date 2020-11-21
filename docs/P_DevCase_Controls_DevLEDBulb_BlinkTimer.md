<document xmlns:msxsl="urn:schemas-microsoft-com:xslt" xmlns:ddue="http://ddue.schemas.microsoft.com/authoring/2003/5" xmlns:xlink="http://www.w3.org/1999/xlink">
<file name="P_DevCase_Controls_DevLEDBulb_BlinkTimer" />
# DevLEDBulb. Property <span id="PageHeader"> </span>
 

**Namespace:** <a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:** DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
private virtual <span class="identifier">Timer</span> BlinkTimer { get; set; }
```

**VB**<br />
``` VB
Private Overridable Property BlinkTimer As <span class="identifier">Timer</span>
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As <span class="identifier">DevLEDBulb</span>
Dim value As <span class="identifier">Timer</span>

value = instance.BlinkTimer

instance.BlinkTimer = value
```

**C++**<br />
``` C++
private:
virtual property <span class="identifier">Timer</span>^ BlinkTimer {
	<span class="identifier">Timer</span>^ get ();
	void set (<span class="identifier">Timer</span>^ value);
}
```

**F#**<br />
``` F#
private abstract BlinkTimer : <span class="identifier">Timer</span> with get, set
private override BlinkTimer : <span class="identifier">Timer</span> with get, set
```


#### Property Value
Type: <span class="nolink">Timer</span><br />\[Missing &lt;value&gt; documentation for "P:DevCase.Controls.DevLEDBulb.BlinkTimer"\]

## See Also<span id="seeAlsoSection"> </span>


#### Reference
<a href="T_DevCase_Controls_DevLEDBulb">DevLEDBulb Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br /></document>