# WebUtil.GeoLocate Method (Uri)
 

Estimates the real-world geographic location of a host.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static GeoInfo GeoLocate(
	Uri uri
)
```

**VB**<br />
``` VB
Public Shared Function GeoLocate ( 
	uri As Uri
) As GeoInfo
```

**VB Usage**<br />
``` VB Usage
Dim uri As Uri
Dim returnValue As GeoInfo

returnValue = WebUtil.GeoLocate(uri)
```

**C++**<br />
``` C++
public:
static GeoInfo^ GeoLocate(
	Uri^ uri
)
```

**F#**<br />
``` F#
static member GeoLocate : 
        uri : Uri -> GeoInfo 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />An Uri pointing to the host for geolocate (eg. "http://google.com").</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_NET_GeoInfo">GeoInfo</a><br />A <a href="T_DevCase_Core_NET_GeoInfo">GeoInfo</a> instance that represents the geographic location info.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>HttpListenerException</td><td>The returned gegraphic location info is empty due to an unknown error. or The server cannot properly process the request. Please, ensure the host name or IP address is valid.</td></tr></table>

## Remarks
About Geolocation: <a href="http://en.wikipedia.org/wiki/Geolocation" target="_blank">http://en.wikipedia.org/wiki/Geolocation</a>

 This geolocation service is powered by: <a href="http://geoiptool.com/" target="_blank">http://geoiptool.com/</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim uri As New Uri("Http://en.wikipedia.org/")
Dim gi As GeoInfo = GeoLocate(uri)

Dim sb As New Global.System.Text.StringBuilder
With sb
    .AppendLine(String.Format("Hostname....: {0}", gi.Hostname))
    .AppendLine(String.Format("Ip Address..: {0}", gi.Ip))
    .AppendLine(String.Format("Country Name: {0}", gi.CountryName))
    .AppendLine(String.Format("Country Code: {0}", gi.CountryCode))
    .AppendLine(String.Format("Region  Name: {0}", gi.RegionName))
    .AppendLine(String.Format("Region  Code: {0}", gi.RegionCode))
    .AppendLine(String.Format("City........: {0}", gi.City))
    .AppendLine(String.Format("Postal Code.: {0}", gi.PostalCode))
    .AppendLine(String.Format("Latitude....: {0}", gi.Latitude))
    .AppendLine(String.Format("Longitude...: {0}", gi.Longitude))
End With

Console.WriteLine(sb.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_GeoLocate">GeoLocate Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />