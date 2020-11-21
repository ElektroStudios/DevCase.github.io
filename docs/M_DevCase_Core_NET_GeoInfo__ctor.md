# GeoInfo Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_NET_GeoInfo">GeoInfo</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public GeoInfo(
	string countryName,
	string countryCode,
	string regionName,
	string regionCode,
	string city,
	string postalCode,
	string hostname,
	string ip,
	string latitude,
	string longitude
)
```

**VB**<br />
``` VB
Public Sub New ( 
	countryName As String,
	countryCode As String,
	regionName As String,
	regionCode As String,
	city As String,
	postalCode As String,
	hostname As String,
	ip As String,
	latitude As String,
	longitude As String
)
```

**VB Usage**<br />
``` VB Usage
Dim countryName As String
Dim countryCode As String
Dim regionName As String
Dim regionCode As String
Dim city As String
Dim postalCode As String
Dim hostname As String
Dim ip As String
Dim latitude As String
Dim longitude As String

Dim instance As New GeoInfo(countryName, 
	countryCode, regionName, regionCode, 
	city, postalCode, hostname, ip, latitude, 
	longitude)
```

**C++**<br />
``` C++
public:
GeoInfo(
	String^ countryName, 
	String^ countryCode, 
	String^ regionName, 
	String^ regionCode, 
	String^ city, 
	String^ postalCode, 
	String^ hostname, 
	String^ ip, 
	String^ latitude, 
	String^ longitude
)
```

**F#**<br />
``` F#
new : 
        countryName : string * 
        countryCode : string * 
        regionName : string * 
        regionCode : string * 
        city : string * 
        postalCode : string * 
        hostname : string * 
        ip : string * 
        latitude : string * 
        longitude : string -> GeoInfo
```


#### Parameters
&nbsp;<dl><dt>countryName</dt><dd>Type: System.String<br />The name of the country.</dd><dt>countryCode</dt><dd>Type: System.String<br />The codename of the country.</dd><dt>regionName</dt><dd>Type: System.String<br />The name of the region.</dd><dt>regionCode</dt><dd>Type: System.String<br />The codename of the region.</dd><dt>city</dt><dd>Type: System.String<br />The name of the city.</dd><dt>postalCode</dt><dd>Type: System.String<br />The postal code.</dd><dt>hostname</dt><dd>Type: System.String<br />The hostname.</dd><dt>ip</dt><dd>Type: System.String<br />The IP address.</dd><dt>latitude</dt><dd>Type: System.String<br />The latitude coordinates.</dd><dt>longitude</dt><dd>Type: System.String<br />The longitude coordinates.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_GeoInfo">GeoInfo Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />