# AlbumInfo Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_FHM_AlbumInfo">AlbumInfo</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public AlbumInfo(
	string id,
	Uri uri,
	string artist,
	string title,
	string country,
	string genre,
	string year,
	IList<string> downloadLinks
)
```

**VB**<br />
``` VB
Public Sub New ( 
	id As String,
	uri As Uri,
	artist As String,
	title As String,
	country As String,
	genre As String,
	year As String,
	downloadLinks As IList(Of String)
)
```

**VB Usage**<br />
``` VB Usage
Dim id As String
Dim uri As Uri
Dim artist As String
Dim title As String
Dim country As String
Dim genre As String
Dim year As String
Dim downloadLinks As IList(Of String)

Dim instance As New AlbumInfo(id, uri, 
	artist, title, country, genre, year, 
	downloadLinks)
```

**C++**<br />
``` C++
public:
AlbumInfo(
	String^ id, 
	Uri^ uri, 
	String^ artist, 
	String^ title, 
	String^ country, 
	String^ genre, 
	String^ year, 
	IList<String^>^ downloadLinks
)
```

**F#**<br />
``` F#
new : 
        id : string * 
        uri : Uri * 
        artist : string * 
        title : string * 
        country : string * 
        genre : string * 
        year : string * 
        downloadLinks : IList<string> -> AlbumInfo
```


#### Parameters
&nbsp;<dl><dt>id</dt><dd>Type: System.String<br />The album identifier>.</dd><dt>uri</dt><dd>Type: System.Uri<br />The album <a href="P_DevCase_ThirdParty_FHM_AlbumInfo_Uri">Uri</a>.</dd><dt>artist</dt><dd>Type: System.String<br />The artist name.</dd><dt>title</dt><dd>Type: System.String<br />The album title.</dd><dt>country</dt><dd>Type: System.String<br />The country of the band/artist.</dd><dt>genre</dt><dd>Type: System.String<br />The music genre.</dd><dt>year</dt><dd>Type: System.String<br />The year that the album has been released.</dd><dt>downloadLinks</dt><dd>Type: System.Collections.Generic.IList(String)<br />The urls to download the album. It can be a single url, or multiple of them.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FHM_AlbumInfo">AlbumInfo Class</a><br /><a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM Namespace</a><br />