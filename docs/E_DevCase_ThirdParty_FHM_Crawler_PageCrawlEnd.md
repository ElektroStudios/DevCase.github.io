# Crawler.PageCrawlEnd Event
 

Occurs when a page is crawled.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<PageCrawlEndEventArgs> PageCrawlEnd
```

**VB**<br />
``` VB
Public Event PageCrawlEnd As EventHandler(Of PageCrawlEndEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Crawler
Dim handler As EventHandler(Of PageCrawlEndEventArgs)

AddHandler instance.PageCrawlEnd, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<PageCrawlEndEventArgs^>^ PageCrawlEnd {
	void add (EventHandler<PageCrawlEndEventArgs^>^ value);
	void remove (EventHandler<PageCrawlEndEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member PageCrawlEnd : IEvent<EventHandler<PageCrawlEndEventArgs>,
    PageCrawlEndEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_FHM_Eventing_PageCrawlEndEventArgs">PageCrawlEndEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FHM_Crawler">Crawler Class</a><br /><a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM Namespace</a><br />