# GoogleMaps.GetMapUrl Method (Double, Double)
 

Builds a Google maps Url given the specified coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Maps">DevCase.ThirdParty.Google.Maps</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetMapUrl(
	double latitude,
	double longitude
)
```

**VB**<br />
``` VB
Public Shared Function GetMapUrl ( 
	latitude As Double,
	longitude As Double
) As String
```

**VB Usage**<br />
``` VB Usage
Dim latitude As Double
Dim longitude As Double
Dim returnValue As String

returnValue = GoogleMaps.GetMapUrl(latitude, 
	longitude)
```

**C++**<br />
``` C++
public:
static String^ GetMapUrl(
	double latitude, 
	double longitude
)
```

**F#**<br />
``` F#
static member GetMapUrl : 
        latitude : float * 
        longitude : float -> string 

```


#### Parameters
&nbsp;<dl><dt>latitude</dt><dd>Type: System.Double<br />The latitude coordinates.</dd><dt>longitude</dt><dd>Type: System.Double<br />The longitude coordinates.</dd></dl>

#### Return Value
Type: String<br />The resulting Google maps Url.

## Examples
This is a code example. 
**VB**<br />
``` VB
' Resulting Url: http://Maps.google.com/?q=39.4767%2C0.3744
Dim url As String = GetGoogleMapsUrl(latitude:=39.4767, longitude:=0.3744)
WebBrowser1.Navigate(url)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Maps_GoogleMaps">GoogleMaps Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Maps_GoogleMaps_GetMapUrl">GetMapUrl Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Maps">DevCase.ThirdParty.Google.Maps Namespace</a><br />