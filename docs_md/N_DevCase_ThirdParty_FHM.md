# DevCase.ThirdParty.FHM Namespace
 




## Classes
&nbsp;<table><tr><th></th><th>Class</th><th>Description</th></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_ThirdParty_FHM_AlbumInfo">AlbumInfo</a></td><td>
Represents the information of an album crawled with <a href="T_DevCase_ThirdParty_FHM_Crawler">Crawler</a>.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_ThirdParty_FHM_Crawler">Crawler</a></td><td>
A crawler that searchs and collect albums (its download links) from the http://freehardmusic.com/ website.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_ThirdParty_FHM_SearchQuery">SearchQuery</a></td><td>
Represents a search query of the http://freehardmusic.com/ website, that is managed by the <a href="M_DevCase_ThirdParty_FHM_Crawler_FetchAlbums">FetchAlbums()</a> and <a href="M_DevCase_ThirdParty_FHM_Crawler_FetchAlbumsAsync">FetchAlbumsAsync()</a> methods. 

 Note that a search query can be performed in two different ways: 

 1. An artist-name based search (<a href="P_DevCase_ThirdParty_FHM_SearchQuery_Artist">Artist</a>). 

 2. A non-artist name based search. That is, a custom search based on country (<a href="P_DevCase_ThirdParty_FHM_SearchQuery_Country">Country</a>), genre (<a href="P_DevCase_ThirdParty_FHM_SearchQuery_Genre">Genre</a>) or year criterias (<a href="P_DevCase_ThirdParty_FHM_SearchQuery_Year">Year</a>); this kind of search can combine the three mentioned criterias, but not the artist name (<a href="P_DevCase_ThirdParty_FHM_SearchQuery_Artist">Artist</a>). 



 So, for an artist-name based search, the value of <a href="P_DevCase_ThirdParty_FHM_SearchQuery_Country">Country</a>, <a href="P_DevCase_ThirdParty_FHM_SearchQuery_Genre">Genre</a> and <a href="P_DevCase_ThirdParty_FHM_SearchQuery_Year">Year</a> properties will always be set to "all". 



 And for a country, genre or year based search, the value of <a href="P_DevCase_ThirdParty_FHM_SearchQuery_Artist">Artist</a> property will always be set to an empty string.</td></tr></table>&nbsp;
