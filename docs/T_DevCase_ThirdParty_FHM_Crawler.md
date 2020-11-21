# Crawler Class
 

A crawler that searchs and collect albums (its download links) from the http://freehardmusic.com/ website.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.FHM.Crawler<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class Crawler : AestheticObject, IDisposable
```

**VB**<br />
``` VB
Public Class Crawler
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As Crawler
```

**C++**<br />
``` C++
public ref class Crawler : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
type Crawler =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The Crawler type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FHM_Crawler__ctor">Crawler</a></td><td>
Initializes a new instance of the Crawler class.</td></tr></table>&nbsp;
<a href="#crawler-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_FHM_Crawler_SearchQuery">SearchQuery</a></td><td>
Gets the search query.</td></tr></table>&nbsp;
<a href="#crawler-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FHM_Crawler_CancelFetchAlbumsAsync">CancelFetchAlbumsAsync</a></td><td>
Aborts a pending fetch operation started by a call to <a href="M_DevCase_ThirdParty_FHM_Crawler_FetchAlbumsAsync">FetchAlbumsAsync()</a> function.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FHM_Crawler_Dispose">Dispose</a></td><td>
Releases all the resources used by this Crawler.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FHM_Crawler_FetchAlbums">FetchAlbums</a></td><td>
Fetch any album found using the current search query.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FHM_Crawler_FetchAlbumsAsync">FetchAlbumsAsync</a></td><td>
Asynchronously fetch any album found using the current search query.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FHM_Crawler_GetAlbumCount">GetAlbumCount</a></td><td>
Gets the count of the albums found using the current search query.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FHM_Crawler_GetAlbumCountAsync">GetAlbumCountAsync</a></td><td>
Asynchronously gets the count of the albums found using the current search query.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FHM_Crawler_ResetSearchQuery">ResetSearchQuery</a></td><td>
Resets the current search query (<a href="P_DevCase_ThirdParty_FHM_Crawler_SearchQuery">SearchQuery</a>) to its default values.</td></tr></table>&nbsp;
<a href="#crawler-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_FHM_Crawler_PageCrawlBegin">PageCrawlBegin</a></td><td>
Occurs when a page is about to be crawled.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_FHM_Crawler_PageCrawlEnd">PageCrawlEnd</a></td><td>
Occurs when a page is crawled.</td></tr></table>&nbsp;
<a href="#crawler-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#crawler-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Imports FHM

Public Module Module1

    Private WithEvents FHMCrawler As New Crawler
    Private mre As New ManualResetEvent(initialState:=False)

    Public Sub Main()
        FHMCrawler.SearchQuery.Artist = "Linkin Park"

        Console.WriteLine("Search Params: {0}", FHMCrawler.SearchQuery.ToString())
        Console.WriteLine()
        Console.WriteLine("Absolute Uri: {0}", FHMCrawler.SearchQuery.Uri.AbsoluteUri)
        Console.WriteLine()
        Console.WriteLine("Retrieving Album count...")
        Dim albumCount As Integer = FHMCrawler.GetAlbumCount()
        Console.WriteLine("Album Count: {0}", albumCount)
        Console.WriteLine()
        Console.WriteLine("Begin crawling, please wait...")
        Fetch()
        mre.WaitOne()
        Console.WriteLine("Done!. Press any key to exit...")
        Console.ReadKey()
    End Sub

    Public Async Sub Fetch()
        Dim success As Boolean = Await FHMCrawler.FetchAlbumsAsync()
        mre.Set()
    End Sub

    Private Sub FHMCrawler_PageCrawlBegin(ByVal sender As Object, e As PageCrawlBeginEventArgs) Handles FHMCrawler.PageCrawlBegin
        Console.WriteLine("[+] Begin crawling page with index: {0}", e.SearchPage)
        Console.WriteLine()
    End Sub

    Private Sub FHMCrawler_PageCrawlEnd(ByVal sender As Object, e As PageCrawlEndEventArgs) Handles FHMCrawler.PageCrawlEnd
        For Each albumInfo As AlbumInfo In e.Albums
            Dim sb As New StringBuilder()
            sb.AppendLine(String.Format("Artist Name.....: {0}", albumInfo.Artist))
            sb.AppendLine(String.Format("Album Title.....: {0}", albumInfo.Title))
            sb.AppendLine(String.Format("Album Year......: {0}", albumInfo.Year))
            sb.AppendLine(String.Format("Album Country...: {0}", albumInfo.Country))
            sb.AppendLine(String.Format("Album Genre.....: {0}", albumInfo.Genre))
            sb.AppendLine(String.Format("Album Id........: {0}", albumInfo.Id))
            sb.AppendLine(String.Format("Album Url.......: {0}", albumInfo.Uri.AbsoluteUri))
            sb.AppendLine(String.Format("Download Link(s): {0}", String.Format("{{ {0} }}", String.Join(", ", albumInfo.DownloadLinks))))
            Console.WriteLine(sb.ToString())
        Next albumInfo
        Console.WriteLine("[+] End crawling page with index: {0}", e.SearchPage)
        Console.WriteLine()
    End Sub

End Module
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM Namespace</a><br />