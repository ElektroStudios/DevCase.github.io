<document xmlns:msxsl="urn:schemas-microsoft-com:xslt" xmlns:ddue="http://ddue.schemas.microsoft.com/authoring/2003/5" xmlns:xlink="http://www.w3.org/1999/xlink">
<file name="P_DevCase_Core_Application_UserInterface_DevMessageBox_TimeoutTimer" />
# DevMessageBox. Property <span id="PageHeader"> </span>
 

**Namespace:** <a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:** DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
private virtual <span class="identifier">Timer</span> TimeoutTimer { get; set; }
```

**VB**<br />
``` VB
Private Overridable Property TimeoutTimer As <span class="identifier">Timer</span>
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As <span class="identifier">DevMessageBox</span>
Dim value As <span class="identifier">Timer</span>

value = instance.TimeoutTimer

instance.TimeoutTimer = value
```

**C++**<br />
``` C++
private:
virtual property <span class="identifier">Timer</span>^ TimeoutTimer {
	<span class="identifier">Timer</span>^ get ();
	void set (<span class="identifier">Timer</span>^ value);
}
```

**F#**<br />
``` F#
private abstract TimeoutTimer : <span class="identifier">Timer</span> with get, set
private override TimeoutTimer : <span class="identifier">Timer</span> with get, set
```


#### Property Value
Type: <span class="nolink">Timer</span><br />\[Missing &lt;value&gt; documentation for "P:DevCase.Core.Application.UserInterface.DevMessageBox.TimeoutTimer"\]

## See Also<span id="seeAlsoSection"> </span>


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_DevMessageBox">DevMessageBox Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br /></document>