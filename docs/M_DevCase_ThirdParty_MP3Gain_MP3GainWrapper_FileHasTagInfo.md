# MP3GainWrapper.FileHasTagInfo Method (FileInfo)
 

Determines whether the specified file contains an `APEv2` tag containing `MP3Gain` information.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Gain">DevCase.ThirdParty.MP3Gain</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool FileHasTagInfo(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Function FileHasTagInfo ( 
	file As FileInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3GainWrapper
Dim file As FileInfo
Dim returnValue As Boolean

returnValue = instance.FileHasTagInfo(file)
```

**C++**<br />
``` C++
public:
bool FileHasTagInfo(
	FileInfo^ file
)
```

**F#**<br />
``` F#
member FileHasTagInfo : 
        file : FileInfo -> bool 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The audio file to analyze.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified file contains an `APEv2` tag containing `MP3Gain` information, otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Gain_MP3GainWrapper">MP3GainWrapper Class</a><br /><a href="Overload_DevCase_ThirdParty_MP3Gain_MP3GainWrapper_FileHasTagInfo">FileHasTagInfo Overload</a><br /><a href="N_DevCase_ThirdParty_MP3Gain">DevCase.ThirdParty.MP3Gain Namespace</a><br />