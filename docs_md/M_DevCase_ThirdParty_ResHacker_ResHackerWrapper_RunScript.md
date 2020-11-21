# ResHackerWrapper.RunScript Method 
 

Runs a ResHacker script.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ResHacker">DevCase.ThirdParty.ResHacker</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int RunScript(
	string filepath
)
```

**VB**<br />
``` VB
Public Function RunScript ( 
	filepath As String
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResHackerWrapper
Dim filepath As String
Dim returnValue As Integer

returnValue = instance.RunScript(filepath)
```

**C++**<br />
``` C++
public:
int RunScript(
	String^ filepath
)
```

**F#**<br />
``` F#
member RunScript : 
        filepath : string -> int 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The script file path.</dd></dl>

#### Return Value
Type: Int32<br />The process exit code.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim exitcode As Integer = ResHacker.RunScript("C:\Reshacker.txt")
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ResHacker_ResHackerWrapper">ResHackerWrapper Class</a><br /><a href="N_DevCase_ThirdParty_ResHacker">DevCase.ThirdParty.ResHacker Namespace</a><br />