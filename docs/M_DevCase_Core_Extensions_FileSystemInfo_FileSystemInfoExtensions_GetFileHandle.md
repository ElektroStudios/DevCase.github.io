# FileSystemInfoExtensions.GetFileHandle Method 
 

Gets a file handle for the specified file or directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_FileSystemInfo">DevCase.Core.Extensions.FileSystemInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static SafeFileHandle GetFileHandle(
	this FileSystemInfo item,
	bool readOnly = true
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetFileHandle ( 
	item As FileSystemInfo,
	Optional readOnly As Boolean = true
) As SafeFileHandle
```

**VB Usage**<br />
``` VB Usage
Dim item As FileSystemInfo
Dim readOnly As Boolean
Dim returnValue As SafeFileHandle

returnValue = item.GetFileHandle(readOnly)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static SafeFileHandle^ GetFileHandle(
	FileSystemInfo^ item, 
	bool readOnly = true
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetFileHandle : 
        item : FileSystemInfo * 
        ?readOnly : bool 
(* Defaults:
        let _readOnly = defaultArg readOnly true
*)
-> SafeFileHandle 

```


#### Parameters
&nbsp;<dl><dt>item</dt><dd>Type: System.IO.FileSystemInfo<br />The source file or directory.</dd><dt>readOnly (Optional)</dt><dd>Type: System.Boolean<br />\[Missing <param name="readOnly"/> documentation for "M:DevCase.Core.Extensions.FileSystemInfo.FileSystemInfoExtensions.GetFileHandle(System.IO.FileSystemInfo,System.Boolean)"\]</dd></dl>

#### Return Value
Type: SafeFileHandle<br />The resulting SafeFileHandle.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type FileSystemInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_FileSystemInfo_FileSystemInfoExtensions">FileSystemInfoExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_FileSystemInfo">DevCase.Core.Extensions.FileSystemInfo Namespace</a><br />