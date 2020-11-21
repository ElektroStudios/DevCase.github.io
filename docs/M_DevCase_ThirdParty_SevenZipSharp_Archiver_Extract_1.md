# Archiver.Extract Method (String, String, String)
 

Extracts the contents of the source compressed archive encrypted with a password, to the specified diretory.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual string Extract(
	string sourceFilePath,
	string outputDirectorypath,
	string password
)
```

**VB**<br />
``` VB
Public Overridable Function Extract ( 
	sourceFilePath As String,
	outputDirectorypath As String,
	password As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As Archiver
Dim sourceFilePath As String
Dim outputDirectorypath As String
Dim password As String
Dim returnValue As String

returnValue = instance.Extract(sourceFilePath, 
	outputDirectorypath, password)
```

**C++**<br />
``` C++
public:
virtual String^ Extract(
	String^ sourceFilePath, 
	String^ outputDirectorypath, 
	String^ password
)
```

**F#**<br />
``` F#
abstract Extract : 
        sourceFilePath : string * 
        outputDirectorypath : string * 
        password : string -> string 
override Extract : 
        sourceFilePath : string * 
        outputDirectorypath : string * 
        password : string -> string 
```


#### Parameters
&nbsp;<dl><dt>sourceFilePath</dt><dd>Type: System.String<br />The source compressed archive.</dd><dt>outputDirectorypath</dt><dd>Type: System.String<br />\[Missing <param name="outputDirectorypath"/> documentation for "M:DevCase.ThirdParty.SevenZipSharp.Archiver.Extract(System.String,System.String,System.String)"\]</dd><dt>password</dt><dd>Type: System.String<br />The password.</dd></dl>

#### Return Value
Type: String<br />The full path of the output directory.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SevenZipSharp_Archiver">Archiver Class</a><br /><a href="Overload_DevCase_ThirdParty_SevenZipSharp_Archiver_Extract">Extract Overload</a><br /><a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />