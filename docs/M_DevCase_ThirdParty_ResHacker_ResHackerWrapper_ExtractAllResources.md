# ResHackerWrapper.ExtractAllResources Method 
 

Extracts all the resources of the specified type from the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ResHacker">DevCase.ThirdParty.ResHacker</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int ExtractAllResources(
	string inputFilepath,
	string outputDirectoryPath,
	ResourceType resourceType
)
```

**VB**<br />
``` VB
Public Function ExtractAllResources ( 
	inputFilepath As String,
	outputDirectoryPath As String,
	resourceType As ResourceType
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResHackerWrapper
Dim inputFilepath As String
Dim outputDirectoryPath As String
Dim resourceType As ResourceType
Dim returnValue As Integer

returnValue = instance.ExtractAllResources(inputFilepath, 
	outputDirectoryPath, resourceType)
```

**C++**<br />
``` C++
public:
int ExtractAllResources(
	String^ inputFilepath, 
	String^ outputDirectoryPath, 
	ResourceType resourceType
)
```

**F#**<br />
``` F#
member ExtractAllResources : 
        inputFilepath : string * 
        outputDirectoryPath : string * 
        resourceType : ResourceType -> int 

```


#### Parameters
&nbsp;<dl><dt>inputFilepath</dt><dd>Type: System.String<br />The source file path.</dd><dt>outputDirectoryPath</dt><dd>Type: System.String<br />The target directory path.</dd><dt>resourceType</dt><dd>Type: <a href="T_DevCase_ThirdParty_ResHacker_ResourceType">DevCase.ThirdParty.ResHacker.ResourceType</a><br />The resource type.</dd></dl>

#### Return Value
Type: Int32<br />The process exit code.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim exitcode As Integer = ResHacker.ExtractAllResources("C:\File.exe", "C:\Directory\", ResourceType.ICON)
Dim exitcode As Integer = ResHacker.ExtractAllResources("C:\File.dll", "C:\Directory\", ResourceType.BITMAP)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ResHacker_ResHackerWrapper">ResHackerWrapper Class</a><br /><a href="N_DevCase_ThirdParty_ResHacker">DevCase.ThirdParty.ResHacker Namespace</a><br />