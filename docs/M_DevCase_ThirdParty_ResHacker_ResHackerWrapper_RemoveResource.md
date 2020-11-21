# ResHackerWrapper.RemoveResource Method 
 

Removes a resource in the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ResHacker">DevCase.ThirdParty.ResHacker</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int RemoveResource(
	string inputFilepath,
	string outputFilepath,
	ResourceType resourceType,
	string resourceName,
	int languageID = 0
)
```

**VB**<br />
``` VB
Public Function RemoveResource ( 
	inputFilepath As String,
	outputFilepath As String,
	resourceType As ResourceType,
	resourceName As String,
	Optional languageID As Integer = 0
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResHackerWrapper
Dim inputFilepath As String
Dim outputFilepath As String
Dim resourceType As ResourceType
Dim resourceName As String
Dim languageID As Integer
Dim returnValue As Integer

returnValue = instance.RemoveResource(inputFilepath, 
	outputFilepath, resourceType, resourceName, 
	languageID)
```

**C++**<br />
``` C++
public:
int RemoveResource(
	String^ inputFilepath, 
	String^ outputFilepath, 
	ResourceType resourceType, 
	String^ resourceName, 
	int languageID = 0
)
```

**F#**<br />
``` F#
member RemoveResource : 
        inputFilepath : string * 
        outputFilepath : string * 
        resourceType : ResourceType * 
        resourceName : string * 
        ?languageID : int 
(* Defaults:
        let _languageID = defaultArg languageID 0
*)
-> int 

```


#### Parameters
&nbsp;<dl><dt>inputFilepath</dt><dd>Type: System.String<br />The source file path.</dd><dt>outputFilepath</dt><dd>Type: System.String<br />The target file path.</dd><dt>resourceType</dt><dd>Type: <a href="T_DevCase_ThirdParty_ResHacker_ResourceType">DevCase.ThirdParty.ResHacker.ResourceType</a><br />The resource type.</dd><dt>resourceName</dt><dd>Type: System.String<br />The resource name.</dd><dt>languageID (Optional)</dt><dd>Type: System.Int32<br />The resource language Id.</dd></dl>

#### Return Value
Type: Int32<br />The process exit code.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim exitcode As Integer = ResHacker.RemoveResource("C:\File.exe", "C:\New File.exe", ResourceType.ICON, "MAINICON", 0)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ResHacker_ResHackerWrapper">ResHackerWrapper Class</a><br /><a href="N_DevCase_ThirdParty_ResHacker">DevCase.ThirdParty.ResHacker Namespace</a><br />