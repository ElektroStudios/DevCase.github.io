# Archiver.Add Method (IEnumerable(String), String)
 

Appends the source file or directory into the specified compressed archive using the default compression parameters.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual string Add(
	IEnumerable<string> sourceFileOrDirs,
	string outputFilepath
)
```

**VB**<br />
``` VB
Public Overridable Function Add ( 
	sourceFileOrDirs As IEnumerable(Of String),
	outputFilepath As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As Archiver
Dim sourceFileOrDirs As IEnumerable(Of String)
Dim outputFilepath As String
Dim returnValue As String

returnValue = instance.Add(sourceFileOrDirs, 
	outputFilepath)
```

**C++**<br />
``` C++
public:
virtual String^ Add(
	IEnumerable<String^>^ sourceFileOrDirs, 
	String^ outputFilepath
)
```

**F#**<br />
``` F#
abstract Add : 
        sourceFileOrDirs : IEnumerable<string> * 
        outputFilepath : string -> string 
override Add : 
        sourceFileOrDirs : IEnumerable<string> * 
        outputFilepath : string -> string 
```


#### Parameters
&nbsp;<dl><dt>sourceFileOrDirs</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The source files or diretories to append.</dd><dt>outputFilepath</dt><dd>Type: System.String<br />The path of the output file to create.</dd></dl>

#### Return Value
Type: String<br />The full path of the resulting compressed archive.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Source file or directory not found.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SevenZipSharp_Archiver">Archiver Class</a><br /><a href="Overload_DevCase_ThirdParty_SevenZipSharp_Archiver_Add">Add Overload</a><br /><a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />