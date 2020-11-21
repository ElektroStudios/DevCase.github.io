# DriveInfoExtensions.GetDriveLetter Method 
 

Gets the drive letter of the source DriveInfo.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DriveInfo">DevCase.Core.Extensions.DriveInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static char GetDriveLetter(
	this DriveInfo sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetDriveLetter ( 
	sender As DriveInfo
) As Char
```

**VB Usage**<br />
``` VB Usage
Dim sender As DriveInfo
Dim returnValue As Char

returnValue = sender.GetDriveLetter()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static wchar_t GetDriveLetter(
	DriveInfo^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetDriveLetter : 
        sender : DriveInfo -> char 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.DriveInfo<br />The source DriveInfo.</dd></dl>

#### Return Value
Type: Char<br />The resulting drive letter.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DriveInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dInfo As DriveInfo = DriveInfo.GetDrives()(0)
Dim dLetter As Char = GetDriveLetter(dInfo)

Console.WriteLine(dLetter)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DriveInfo_DriveInfoExtensions">DriveInfoExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_DriveInfo">DevCase.Core.Extensions.DriveInfo Namespace</a><br />