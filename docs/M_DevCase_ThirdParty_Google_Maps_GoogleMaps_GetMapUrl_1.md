# GoogleMaps.GetMapUrl Method (String, String, String, String)
 

Builds a Google maps Url given the specified geographic parameters.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Maps">DevCase.ThirdParty.Google.Maps</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetMapUrl(
	string state = "",
	string city = "",
	string street = "",
	string zipcode = ""
)
```

**VB**<br />
``` VB
Public Shared Function GetMapUrl ( 
	Optional state As String = "",
	Optional city As String = "",
	Optional street As String = "",
	Optional zipcode As String = ""
) As String
```

**VB Usage**<br />
``` VB Usage
Dim state As String
Dim city As String
Dim street As String
Dim zipcode As String
Dim returnValue As String

returnValue = GoogleMaps.GetMapUrl(state, 
	city, street, zipcode)
```

**C++**<br />
``` C++
public:
static String^ GetMapUrl(
	String^ state = L"", 
	String^ city = L"", 
	String^ street = L"", 
	String^ zipcode = L""
)
```

**F#**<br />
``` F#
static member GetMapUrl : 
        ?state : string * 
        ?city : string * 
        ?street : string * 
        ?zipcode : string 
(* Defaults:
        let _state = defaultArg state ""
        let _city = defaultArg city ""
        let _street = defaultArg street ""
        let _zipcode = defaultArg zipcode ""
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>state (Optional)</dt><dd>Type: System.String<br />The state name.</dd><dt>city (Optional)</dt><dd>Type: System.String<br />The city name.</dd><dt>street (Optional)</dt><dd>Type: System.String<br />The street name.</dd><dt>zipcode (Optional)</dt><dd>Type: System.String<br />The zip-code.</dd></dl>

#### Return Value
Type: String<br />The resulting Google maps Url.

## Examples
This is a code example. 
**VB**<br />
``` VB
' Resulting Url: http://Maps.google.com/?q=Valencia,+España
Dim url As String = GetGoogleMapsUrl(state:="España", city:="Valencia")
WebBrowser1.Navigate(url)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Maps_GoogleMaps">GoogleMaps Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Maps_GoogleMaps_GetMapUrl">GetMapUrl Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Maps">DevCase.ThirdParty.Google.Maps Namespace</a><br />