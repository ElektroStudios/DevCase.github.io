# Crawler.GetAlbumCountAsync Method 
 

Asynchronously gets the count of the albums found using the current search query.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual Task<int> GetAlbumCountAsync()
```

**VB**<br />
``` VB
Public Overridable Function GetAlbumCountAsync As Task(Of Integer)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Crawler
Dim returnValue As Task(Of Integer)

returnValue = instance.GetAlbumCountAsync()
```

**C++**<br />
``` C++
public:
virtual Task<int>^ GetAlbumCountAsync()
```

**F#**<br />
``` F#
abstract GetAlbumCountAsync : unit -> Task<int> 
override GetAlbumCountAsync : unit -> Task<int> 
```


#### Return Value
Type: Task(Int32)<br />The count of the albums found using the current search query.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FHM_Crawler">Crawler Class</a><br /><a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM Namespace</a><br />