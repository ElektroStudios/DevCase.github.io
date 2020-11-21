# Crawler.PageCrawlBegin Event
 

Occurs when a page is about to be crawled.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<PageCrawlBeginEventArgs> PageCrawlBegin
```

**VB**<br />
``` VB
Public Event PageCrawlBegin As EventHandler(Of PageCrawlBeginEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Crawler
Dim handler As EventHandler(Of PageCrawlBeginEventArgs)

AddHandler instance.PageCrawlBegin, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<PageCrawlBeginEventArgs^>^ PageCrawlBegin {
	void add (EventHandler<PageCrawlBeginEventArgs^>^ value);
	void remove (EventHandler<PageCrawlBeginEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member PageCrawlBegin : IEvent<EventHandler<PageCrawlBeginEventArgs>,
    PageCrawlBeginEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_FHM_Eventing_PageCrawlBeginEventArgs">PageCrawlBeginEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FHM_Crawler">Crawler Class</a><br /><a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM Namespace</a><br />