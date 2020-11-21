# FileInfoExtensions.Lock Method (FileInfo)
 

Locks read/write access to the specified file for other applications (during the lifetime of the current application). 

 To unlock the file, just dispose the returned FileStream object.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static FileStream Lock(
	this FileInfo sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Lock ( 
	sender As FileInfo
) As FileStream
```

**VB Usage**<br />
``` VB Usage
Dim sender As FileInfo
Dim returnValue As FileStream

returnValue = sender.Lock()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static FileStream^ Lock(
	FileInfo^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Lock : 
        sender : FileInfo -> FileStream 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.FileInfo<br />The source FileInfo.</dd></dl>

#### Return Value
Type: FileStream<br />A FileStream object that represents the file stream.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type FileInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim file As New FileInfo("C:\File.ext")
Using fs As FileStream = file.Lock()
 ' ...
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_FileInfo_FileInfoExtensions">FileInfoExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_Lock">Lock Overload</a><br /><a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo Namespace</a><br />