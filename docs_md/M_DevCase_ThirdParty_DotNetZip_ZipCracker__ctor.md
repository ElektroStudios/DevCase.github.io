# ZipCracker Constructor (FileInfo)
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_DotNetZip_ZipCracker">ZipCracker</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ZipCracker(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Sub New ( 
	file As FileInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo

Dim instance As New ZipCracker(file)
```

**C++**<br />
``` C++
public:
ZipCracker(
	FileInfo^ file
)
```

**F#**<br />
``` F#
new : 
        file : FileInfo -> ZipCracker
```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The encrypted .zip archive.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td /></tr><tr><td>ZipException</td><td /></tr><tr><td>IOException</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetZip_ZipCracker">ZipCracker Class</a><br /><a href="Overload_DevCase_ThirdParty_DotNetZip_ZipCracker__ctor">ZipCracker Overload</a><br /><a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip Namespace</a><br />