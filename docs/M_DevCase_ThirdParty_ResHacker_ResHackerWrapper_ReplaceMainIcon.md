# ResHackerWrapper.ReplaceMainIcon Method 
 

Replaces the main icon of the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ResHacker">DevCase.ThirdParty.ResHacker</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int ReplaceMainIcon(
	string inputFilepath,
	string outputFilepath,
	string iconFilepath
)
```

**VB**<br />
``` VB
Public Function ReplaceMainIcon ( 
	inputFilepath As String,
	outputFilepath As String,
	iconFilepath As String
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResHackerWrapper
Dim inputFilepath As String
Dim outputFilepath As String
Dim iconFilepath As String
Dim returnValue As Integer

returnValue = instance.ReplaceMainIcon(inputFilepath, 
	outputFilepath, iconFilepath)
```

**C++**<br />
``` C++
public:
int ReplaceMainIcon(
	String^ inputFilepath, 
	String^ outputFilepath, 
	String^ iconFilepath
)
```

**F#**<br />
``` F#
member ReplaceMainIcon : 
        inputFilepath : string * 
        outputFilepath : string * 
        iconFilepath : string -> int 

```


#### Parameters
&nbsp;<dl><dt>inputFilepath</dt><dd>Type: System.String<br />The source file path.</dd><dt>outputFilepath</dt><dd>Type: System.String<br />The target file path.</dd><dt>iconFilepath</dt><dd>Type: System.String<br />The source icon file path.</dd></dl>

#### Return Value
Type: Int32<br />The process exit code.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim exitcode As Integer = ResHacker.ReplaceMainIcon("c:\file.exe", "c:\new file.exe", "c:\icon.ico")
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ResHacker_ResHackerWrapper">ResHackerWrapper Class</a><br /><a href="N_DevCase_ThirdParty_ResHacker">DevCase.ThirdParty.ResHacker Namespace</a><br />