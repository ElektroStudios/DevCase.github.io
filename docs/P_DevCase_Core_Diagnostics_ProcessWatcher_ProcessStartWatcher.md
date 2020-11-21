<document xmlns:msxsl="urn:schemas-microsoft-com:xslt" xmlns:ddue="http://ddue.schemas.microsoft.com/authoring/2003/5" xmlns:xlink="http://www.w3.org/1999/xlink">
<file name="P_DevCase_Core_Diagnostics_ProcessWatcher_ProcessStartWatcher" />
# ProcessWatcher. Property <span id="PageHeader"> </span>
 

**Namespace:** <a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics</a><br />**Assembly:** DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
private virtual <span class="identifier">ManagementEventWatcher</span> ProcessStartWatcher { get; set; }
```

**VB**<br />
``` VB
Private Overridable Property ProcessStartWatcher As <span class="identifier">ManagementEventWatcher</span>
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As <span class="identifier">ProcessWatcher</span>
Dim value As <span class="identifier">ManagementEventWatcher</span>

value = instance.ProcessStartWatcher

instance.ProcessStartWatcher = value
```

**C++**<br />
``` C++
private:
virtual property <span class="identifier">ManagementEventWatcher</span>^ ProcessStartWatcher {
	<span class="identifier">ManagementEventWatcher</span>^ get ();
	void set (<span class="identifier">ManagementEventWatcher</span>^ value);
}
```

**F#**<br />
``` F#
private abstract ProcessStartWatcher : <span class="identifier">ManagementEventWatcher</span> with get, set
private override ProcessStartWatcher : <span class="identifier">ManagementEventWatcher</span> with get, set
```


#### Property Value
Type: <span class="nolink">ManagementEventWatcher</span><br />\[Missing &lt;value&gt; documentation for "P:DevCase.Core.Diagnostics.ProcessWatcher.ProcessStartWatcher"\]

## See Also<span id="seeAlsoSection"> </span>


#### Reference
<a href="T_DevCase_Core_Diagnostics_ProcessWatcher">ProcessWatcher Class</a><br /><a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics Namespace</a><br /></document>