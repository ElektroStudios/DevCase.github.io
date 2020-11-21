# GeckoFxUtil.BackoffCount Property 
 

Gets or sets the maximum number of times the content of a webpage will do timer-based reflows. 

 Rather than wait until a page has completely downloaded to display it to the user, Mozilla applications will periodically render what has been received to that point. 

 Because reflowing the page every time additional data is received greatly slows down total page load time, a timer was added so that the page would not reflow too often. 

 After this number has been reached, the page will only reflow once it is finished downloading.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int BackoffCount { get; set; }
```

**VB**<br />
``` VB
Public Shared Property BackoffCount As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = GeckoFxUtil.BackoffCount

GeckoFxUtil.BackoffCount = value
```

**C++**<br />
``` C++
public:
static property int BackoffCount {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member BackoffCount : int with get, set

```


#### Property Value
Type: Int32<br />The maximum number of times the content of a webpage will do timer-based reflows.

## Remarks
Recommended value: `5`

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GeckoFx_GeckoFxUtil">GeckoFxUtil Class</a><br /><a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx Namespace</a><br />