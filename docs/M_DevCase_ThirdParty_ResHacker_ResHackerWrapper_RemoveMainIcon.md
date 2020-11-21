# ResHackerWrapper.RemoveMainIcon Method 
 

Deletes the main icon of the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ResHacker">DevCase.ThirdParty.ResHacker</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int RemoveMainIcon(
	string inputFilepath,
	string outputFilepath
)
```

**VB**<br />
``` VB
Public Function RemoveMainIcon ( 
	inputFilepath As String,
	outputFilepath As String
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResHackerWrapper
Dim inputFilepath As String
Dim outputFilepath As String
Dim returnValue As Integer

returnValue = instance.RemoveMainIcon(inputFilepath, 
	outputFilepath)
```

**C++**<br />
``` C++
public:
int RemoveMainIcon(
	String^ inputFilepath, 
	String^ outputFilepath
)
```

**F#**<br />
``` F#
member RemoveMainIcon : 
        inputFilepath : string * 
        outputFilepath : string -> int 

```


#### Parameters
&nbsp;<dl><dt>inputFilepath</dt><dd>Type: System.String<br />The source file path.</dd><dt>outputFilepath</dt><dd>Type: System.String<br />The target file path.</dd></dl>

#### Return Value
Type: Int32<br />The process exit code.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim exitcode As Integer = ResHacker.RemoveMainIcon("c:\file.exe", "c:\new file.exe")
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ResHacker_ResHackerWrapper">ResHackerWrapper Class</a><br /><a href="N_DevCase_ThirdParty_ResHacker">DevCase.ThirdParty.ResHacker Namespace</a><br />