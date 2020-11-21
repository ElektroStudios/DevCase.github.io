# FileInfoExtensions.ToShellFile Method 
 

Converts the specified FileInfo to ShellFile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static ShellFile ToShellFile(
	this FileInfo sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToShellFile ( 
	sender As FileInfo
) As ShellFile
```

**VB Usage**<br />
``` VB Usage
Dim sender As FileInfo
Dim returnValue As ShellFile

returnValue = sender.ToShellFile()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static ShellFile^ ToShellFile(
	FileInfo^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToShellFile : 
        sender : FileInfo -> ShellFile 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.FileInfo<br />The source FileInfo.</dd></dl>

#### Return Value
Type: ShellFile<br />The resulting ShellFile

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type FileInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example to get the DisplayArtist property of MP3 audio files. 
**VB**<br />
``` VB
For Each file As FileInfo In New DirectoryInfo("C:\Music\").GetFiles("*.mp3", SearchOption.TopDirectoryOnly)
    Dim sFile As ShellFile = file.ToShellFile()
    Dim propValue As String = sFile.Properties.System.Music.DisplayArtist.Value
    Console.WriteLine(propValue)
Next
```


## Examples
This is a code example to get the Title property of a true type font. 
**VB**<br />
``` VB
Dim diInfo As New DirectoryInfo("C:\Fonts\")

For Each fiInfo As FileInfo In diInfo.GetFiles("*.ttf", SearchOption.TopDirectoryOnly)
    Dim sFile As ShellFile = ShellFile.FromFilePath(fiInfo.FullName)
    Dim title As String = sFile.Properties.System.Title.Value

    Dim sb As New StringBuilder()
    sb.AppendLine(String.Format("Name.: {0}", fiInfo.Name))
    ' Generate same font title as shown at 'HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Fonts' key.
    sb.AppendLine(String.Format("Title: ""{0} (TrueType)""", title)) 

    Console.WriteLine(sb.ToString())
Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_FileInfo_FileInfoExtensions">FileInfoExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo Namespace</a><br />