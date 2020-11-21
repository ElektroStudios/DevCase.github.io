# FileInfoExtensions.OrderByLastAccessTime Method 
 

Sorts the elements of the source IEnumerable(T) by their LastAccessTime property.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IOrderedEnumerable<FileInfo> OrderByLastAccessTime(
	this IEnumerable<FileInfo> sequence,
	ListSortDirection sortDirection
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function OrderByLastAccessTime ( 
	sequence As IEnumerable(Of FileInfo),
	sortDirection As ListSortDirection
) As IOrderedEnumerable(Of FileInfo)
```

**VB Usage**<br />
``` VB Usage
Dim sequence As IEnumerable(Of FileInfo)
Dim sortDirection As ListSortDirection
Dim returnValue As IOrderedEnumerable(Of FileInfo)

returnValue = sequence.OrderByLastAccessTime(sortDirection)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IOrderedEnumerable<FileInfo^>^ OrderByLastAccessTime(
	IEnumerable<FileInfo^>^ sequence, 
	ListSortDirection sortDirection
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member OrderByLastAccessTime : 
        sequence : IEnumerable<FileInfo> * 
        sortDirection : ListSortDirection -> IOrderedEnumerable<FileInfo> 

```


#### Parameters
&nbsp;<dl><dt>sequence</dt><dd>Type: System.Collections.Generic.IEnumerable(FileInfo)<br />The source IEnumerable(T).</dd><dt>sortDirection</dt><dd>Type: System.ComponentModel.ListSortDirection<br />A value that determine to sort the elements in ascending or descending order.</dd></dl>

#### Return Value
Type: IOrderedEnumerable(FileInfo)<br />The resulting IEnumerable(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(FileInfo). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dir As New DirectoryInfo("C:\Windows")
Dim files As IEnumerable(Of FileInfo) = From fi As FileInfo In dir.EnumerateFiles("*", SearchOption.TopDirectoryOnly)
Dim sortedFiles As IOrderedEnumerable(Of FileInfo) = IEnumerableExtensions.OrderByLastAccessTime(files, ListSortDirection.Ascending)
Dim formatProvider As IFormatProvider = CultureInfo.GetCultureInfo("es-ES").DateTimeFormat

For Each file As FileInfo In sortedFiles
    Console.WriteLine($"Last Access Time: {file.LastAccessTime.ToString(formatProvider)}, Name: {file.Name}")
Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_FileInfo_FileInfoExtensions">FileInfoExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo Namespace</a><br />