# AssocStr Enumeration
 

Used by `IQueryAssociations::GetString` to define the type of string that is to be returned.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum AssocStr
```

**VB**<br />
``` VB
Public Enumeration AssocStr
```

**VB Usage**<br />
``` VB Usage
Dim instance As AssocStr
```

**C++**<br />
``` C++
public enum class AssocStr
```

**F#**<br />
``` F#
type AssocStr
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.Command">**Command**</td><td>1</td><td>A command string associated with a Shell verb.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.Executable">**Executable**</td><td>2</td><td>An executable from a Shell verb command string. 

 For example, this string is found as the (Default) value for a subkey such as HKEY_CLASSES_ROOT\ApplicationName\shell\Open\command. 

 If the command uses Rundll.exe, set the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_AssocF">RemapRunDll</a> flag in the flags parameter of `IQueryAssociations::GetString` to retrieve the target executable.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.FriendlyDocName">**FriendlyDocName**</td><td>3</td><td>The friendly name of a document type.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.FriendlyAppName">**FriendlyAppName**</td><td>4</td><td>The friendly name of an executable file.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.NoOpen">**NoOpen**</td><td>5</td><td>Ignore the information associated with the open subkey.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.ShellNewValue">**ShellNewValue**</td><td>6</td><td>Look under the ShellNew subkey.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.DdeCommand">**DdeCommand**</td><td>7</td><td>A template for DDE commands.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.DdeIfExec">**DdeIfExec**</td><td>8</td><td>The DDE command to use to create a process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.DdeApplication">**DdeApplication**</td><td>9</td><td>The application name in a DDE broadcast.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.DdeTopic">**DdeTopic**</td><td>10</td><td>The topic name in a DDE broadcast.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.InfoTip">**InfoTip**</td><td>11</td><td>Corresponds to the InfoTip registry value. 

 Returns an info tip for an item, or list of properties in the form of an `IPropertyDescriptionList` from which to create an info tip, such as when hovering the cursor over a file name. 

 The list of properties can be parsed with `PSGetPropertyDescriptionListFromString`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.QuickTip">**QuickTip**</td><td>12</td><td>Corresponds to the QuickTip registry value. Same as InfoTip, except that it always returns a list of property names in the form of an `IPropertyDescriptionList`. 

 The difference between this value and InfoTip is that this returns properties that are safe for any scenario that causes slow property retrieval, such as offline or slow networks. 

 Some of the properties returned from InfoTip might not be appropriate for slow property retrieval scenarios. 

 The list of properties can be parsed with `PSGetPropertyDescriptionListFromString`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.TileInfo">**TileInfo**</td><td>13</td><td>Corresponds to the TileInfo registry value. 

 Contains a list of properties to be displayed for a particular file type in a Windows Explorer window that is in tile view. 

 This is the same as InfoTip, but, like QuickTip, it also returns a list of property names in the form of an `IPropertyDescriptionList`. 

 The list of properties can be parsed with `PSGetPropertyDescriptionListFromString`</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.ContentType">**ContentType**</td><td>14</td><td>Describes a general type of MIME file association, such as image and bmp, so that applications can make general assumptions about a specific file type.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.DefaultIcon">**DefaultIcon**</td><td>15</td><td>Returns the path to the icon resources to use by default for this association. 

 Positive numbers indicate an index into the dll's resource table, while negative numbers indicate a resource ID. 

 An example of the syntax for the resource is "C:\myfolder\myfile.dll,-1".</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.ShellExtension">**ShellExtension**</td><td>16</td><td>For an object that has a Shell extension associated with it, you can use this to retrieve the CLSID of that Shell extension object by passing a string representation of the IID of the interface you want to retrieve as the `pwszExtra` parameter of `IQueryAssociations::GetString`. 

 For example, if you want to retrieve a handler that implements the IExtractImage interface, you would specify "{BB2E617C-0920-11d1-9A0B-00C04FC2D6C1}", which is the IID of IExtractImage.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.DropTarget">**DropTarget**</td><td>17</td><td>For a verb invoked through COM and the `IDropTarget` interface, you can use this flag to retrieve the `IDropTarget` object's CLSID. 

 This CLSID is registered in the DropTarget subkey. 

 The verb is specified in the pwszExtra parameter in the call to `IQueryAssociations::GetString`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.DelegateExecute">**DelegateExecute**</td><td>18</td><td>For a verb invoked through COM and the `IExecuteCommand` interface, you can use this flag to retrieve the `IExecuteCommand` object's CLSID. 

 This CLSID is registered in the verb's command subkey as the `DelegateExecute` entry. 

 The verb is specified in the `pwszExtra` parameter in the call to `IQueryAssociations::GetString`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.SupportedUriProtocols">**SupportedUriProtocols**</td><td>19</td><td>Introduced in Windows 8. 

 There is no official documentation for this flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocStr.Maximum">**Maximum**</td><td>20</td><td>The maximum defined AssocStr value, used for validation purposes.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762475%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762475%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />