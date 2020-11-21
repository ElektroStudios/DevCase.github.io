# Crawler.FetchAlbumsAsync Method 
 

Asynchronously fetch any album found using the current search query.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual Task<bool> FetchAlbumsAsync()
```

**VB**<br />
``` VB
Public Overridable Function FetchAlbumsAsync As Task(Of Boolean)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Crawler
Dim returnValue As Task(Of Boolean)

returnValue = instance.FetchAlbumsAsync()
```

**C++**<br />
``` C++
public:
virtual Task<bool>^ FetchAlbumsAsync()
```

**F#**<br />
``` F#
abstract FetchAlbumsAsync : unit -> Task<bool> 
override FetchAlbumsAsync : unit -> Task<bool> 
```


#### Return Value
Type: Task(Boolean)<br />Returns `false` (`False` in Visual Basic) if the fetch operation was canceled by a call to <a href="M_DevCase_ThirdParty_FHM_Crawler_CancelFetchAlbumsAsync">CancelFetchAlbumsAsync()</a> method.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FHM_Crawler">Crawler Class</a><br /><a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM Namespace</a><br />