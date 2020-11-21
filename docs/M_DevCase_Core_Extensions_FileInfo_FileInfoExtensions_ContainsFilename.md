# FileInfoExtensions.ContainsFilename Method 
 

Determines whether the source IEnumerable(T) contains an element with the specified file name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool ContainsFilename(
	this IEnumerable<FileInfo> sequence,
	string name,
	StringComparison comparisonType
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ContainsFilename ( 
	sequence As IEnumerable(Of FileInfo),
	name As String,
	comparisonType As StringComparison
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sequence As IEnumerable(Of FileInfo)
Dim name As String
Dim comparisonType As StringComparison
Dim returnValue As Boolean

returnValue = sequence.ContainsFilename(name, 
	comparisonType)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool ContainsFilename(
	IEnumerable<FileInfo^>^ sequence, 
	String^ name, 
	StringComparison comparisonType
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ContainsFilename : 
        sequence : IEnumerable<FileInfo> * 
        name : string * 
        comparisonType : StringComparison -> bool 

```


#### Parameters
&nbsp;<dl><dt>sequence</dt><dd>Type: System.Collections.Generic.IEnumerable(FileInfo)<br />The source IEnumerable(T).</dd><dt>name</dt><dd>Type: System.String<br />\[Missing <param name="name"/> documentation for "M:DevCase.Core.Extensions.FileInfo.FileInfoExtensions.ContainsFilename(System.Collections.Generic.IEnumerable{System.IO.FileInfo},System.String,System.StringComparison)"\]</dd><dt>comparisonType</dt><dd>Type: System.StringComparison<br />\[Missing <param name="comparisonType"/> documentation for "M:DevCase.Core.Extensions.FileInfo.FileInfoExtensions.ContainsFilename(System.Collections.Generic.IEnumerable{System.IO.FileInfo},System.String,System.StringComparison)"\]</dd></dl>

#### Return Value
Type: Boolean<br />True if the source IEnumerable(T) contains an element with the specified file name; otherwise, False.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(FileInfo). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_FileInfo_FileInfoExtensions">FileInfoExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo Namespace</a><br />