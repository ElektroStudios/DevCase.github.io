# LibVideoUtil.SaveVideoToDiskAsync Method (String, String)
 

Asynchronously downloads a Youtube video to disk.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_LibVideo">DevCase.ThirdParty.LibVideo</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SaveVideoToDiskAsync(
	string url,
	string dirPath
)
```

**VB**<br />
``` VB
Public Shared Sub SaveVideoToDiskAsync ( 
	url As String,
	dirPath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim dirPath As StringLibVideoUtil.SaveVideoToDiskAsync(url, dirPath)
```

**C++**<br />
``` C++
public:
static void SaveVideoToDiskAsync(
	String^ url, 
	String^ dirPath
)
```

**F#**<br />
``` F#
static member SaveVideoToDiskAsync : 
        url : string * 
        dirPath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The Youtube video Url.</dd><dt>dirPath</dt><dd>Type: System.String<br />The directory path where to save the downloaded video.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_LibVideo_LibVideoUtil">LibVideoUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_LibVideo_LibVideoUtil_SaveVideoToDiskAsync">SaveVideoToDiskAsync Overload</a><br /><a href="N_DevCase_ThirdParty_LibVideo">DevCase.ThirdParty.LibVideo Namespace</a><br />