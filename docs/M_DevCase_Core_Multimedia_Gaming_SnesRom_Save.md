# SnesRom.Save Method 
 

Save the ROM changes to the specified file path.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Save(
	string filePath,
	bool replace
)
```

**VB**<br />
``` VB
Public Sub Save ( 
	filePath As String,
	replace As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As SnesRom
Dim filePath As String
Dim replace As Boolean

instance.Save(filePath, replace)
```

**C++**<br />
``` C++
public:
void Save(
	String^ filePath, 
	bool replace
)
```

**F#**<br />
``` F#
member Save : 
        filePath : string * 
        replace : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />The ROM file path.</dd><dt>replace</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), replaces any existing file, otherwise, it will throw throws a IOException if the target file already exists.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>IOException</td><td>The target file already exists.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Gaming_SnesRom">SnesRom Class</a><br /><a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming Namespace</a><br />