# TweakingUtil.SystemDateTime Property 
 

Gets or sets the system date and time.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DateTime SystemDateTime { get; set; }
```

**VB**<br />
``` VB
Public Shared Property SystemDateTime As DateTime
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As DateTime

value = TweakingUtil.SystemDateTime

TweakingUtil.SystemDateTime = value
```

**C++**<br />
``` C++
public:
static property DateTime SystemDateTime {
	DateTime get ();
	void set (DateTime value);
}
```

**F#**<br />
``` F#
static member SystemDateTime : DateTime with get, set

```


#### Property Value
Type: DateTime<br />The system date and time.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dateAndTime As New Date(year:=2000, month:=1, day:=1,
                            hour:=0, minute:=0, second:=0)

Dim dateOnly As New Date(year:=2000, month:=1, day:=1,
                         hour:=Date.Now.Hour, minute:=Date.Now.Minute, second:=Date.Now.Second)

Dim timeOnly As New Date(year:=Date.Today.Year, month:=Date.Today.Month, day:=Date.Today.Day,
                         hour:=0, minute:=0, second:=0)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />