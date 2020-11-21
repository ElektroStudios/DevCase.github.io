<document xmlns:msxsl="urn:schemas-microsoft-com:xslt" xmlns:ddue="http://ddue.schemas.microsoft.com/authoring/2003/5" xmlns:xlink="http://www.w3.org/1999/xlink">
<file name="P_DevCase_Core_Diagnostics_DebuggerNotify_DebuggerCheckTimer" />
# DebuggerNotify. Property <span id="PageHeader"> </span>
 

**Namespace:** <a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics</a><br />**Assembly:** DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
private virtual <span class="identifier">Timer</span> DebuggerCheckTimer { get; set; }
```

**VB**<br />
``` VB
Private Overridable Property DebuggerCheckTimer As <span class="identifier">Timer</span>
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As <span class="identifier">DebuggerNotify</span>
Dim value As <span class="identifier">Timer</span>

value = instance.DebuggerCheckTimer

instance.DebuggerCheckTimer = value
```

**C++**<br />
``` C++
private:
virtual property <span class="identifier">Timer</span>^ DebuggerCheckTimer {
	<span class="identifier">Timer</span>^ get ();
	void set (<span class="identifier">Timer</span>^ value);
}
```

**F#**<br />
``` F#
private abstract DebuggerCheckTimer : <span class="identifier">Timer</span> with get, set
private override DebuggerCheckTimer : <span class="identifier">Timer</span> with get, set
```


#### Property Value
Type: <span class="nolink">Timer</span><br />\[Missing &lt;value&gt; documentation for "P:DevCase.Core.Diagnostics.DebuggerNotify.DebuggerCheckTimer"\]

## See Also<span id="seeAlsoSection"> </span>


#### Reference
<a href="T_DevCase_Core_Diagnostics_DebuggerNotify">DebuggerNotify Class</a><br /><a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics Namespace</a><br /></document>