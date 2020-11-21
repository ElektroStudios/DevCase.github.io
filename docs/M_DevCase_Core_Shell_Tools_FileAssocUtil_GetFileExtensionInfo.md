# FileAssocUtil.GetFileExtensionInfo Method 
 

Gets the system information of the specified file extension.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static FileExtensionInfo GetFileExtensionInfo(
	string extensionName
)
```

**VB**<br />
``` VB
Public Shared Function GetFileExtensionInfo ( 
	extensionName As String
) As FileExtensionInfo
```

**VB Usage**<br />
``` VB Usage
Dim extensionName As String
Dim returnValue As FileExtensionInfo

returnValue = FileAssocUtil.GetFileExtensionInfo(extensionName)
```

**C++**<br />
``` C++
public:
static FileExtensionInfo^ GetFileExtensionInfo(
	String^ extensionName
)
```

**F#**<br />
``` F#
static member GetFileExtensionInfo : 
        extensionName : string -> FileExtensionInfo 

```


#### Parameters
&nbsp;<dl><dt>extensionName</dt><dd>Type: System.String<br />The extension name (eg: .txt).</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Shell_FileExtensionInfo">FileExtensionInfo</a><br />A <a href="T_DevCase_Core_Shell_FileExtensionInfo">FileExtensionInfo</a> object that contains the file extension info.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>extensionName</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim feInfo As FileExtensionInfo = FileAssoc.GetFileExtensionInfo(".wav")

Dim sb As New Global.System.Text.StringBuilder
With sb
    .AppendLine(String.Format("Extension Name: {0}", feInfo.Name))
    .AppendLine(String.Format("Friendly Doc Name: {0}", feInfo.FriendlyDocName))
    .AppendLine(String.Format("Content Type: {0}", feInfo.ContentType))
    .AppendLine(String.Format("Default Icon: {0}", feInfo.DefaultIcon))
    .AppendLine("-----------------------------------------------------------")
    .AppendLine(String.Format("Friendly App Name: {0}", feInfo.FriendlyAppName))
    .AppendLine(String.Format("Executable: {0}", feInfo.Executable))
    .AppendLine(String.Format("Command: {0}", feInfo.Command))
    .AppendLine("-----------------------------------------------------------")
    .AppendLine(String.Format("Drop Target: {0}", feInfo.DropTarget))
    .AppendLine(String.Format("Info Tip: {0}", feInfo.InfoTip))
    .AppendLine(String.Format("No Open: {0}", feInfo.NoOpen))
    .AppendLine(String.Format("Shell Extension: {0}", feInfo.ShellExtension))
    .AppendLine(String.Format("Shell New Value: {0}", feInfo.ShellNewValue))
    .AppendLine("-----------------------------------------------------------")
    .AppendLine(String.Format("Supported URI Protocols: {0}", feInfo.SupportedUriProtocols))
    .AppendLine(String.Format("DDE Application: {0}", feInfo.DdeApplication))
    .AppendLine(String.Format("DDE Command: {0}", feInfo.DdeCommand))
    .AppendLine(String.Format("DDE If Exec: {0}", feInfo.DdeIfExec))
    .AppendLine(String.Format("DDE Topic: {0}", feInfo.DdeTopic))
End With

MessageBox.Show(sb.ToString(), "", MessageBoxButtons.OK, MessageBoxIcon.Information)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_FileAssocUtil">FileAssocUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />