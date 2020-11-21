# FileExtensionInfo Properties
 

The <a href="T_DevCase_Core_Shell_FileExtensionInfo">FileExtensionInfo</a> type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_Command">Command</a></td><td>
Gets a command string associated with a Shell verb.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_ContentType">ContentType</a></td><td>
Gets a general type of MIME file association, such as 'image' and 'bmp', so that applications can make general assumptions about a specific file type.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_DdeApplication">DdeApplication</a></td><td>
Gets the application name in a DDE broadcast.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_DdeCommand">DdeCommand</a></td><td>
Gets a template for DDE commands.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_DdeIfExec">DdeIfExec</a></td><td>
Gets the DDE command to use to create a process.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_DdeTopic">DdeTopic</a></td><td>
Gets the topic name in a DDE broadcast.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_DefaultIcon">DefaultIcon</a></td><td>
Gets the path to the icon resources to use by default for this association. 

 Positive numbers indicate an index into the dll's resource table, while negative numbers indicate a resource ID. 

 An example of the syntax for the resource is "C:\myfolder\myfile.dll,-1".</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_DelegateExecute">DelegateExecute</a></td><td>
For a verb invoked through COM and the `IExecuteCommand` interface, you can use this flag to retrieve the `IExecuteCommand` object's CLSID. 

 This CLSID is registered in the verb's command subkey as the `DelegateExecute` entry. 

 The verb is specified in the pwszExtra parameter in the call to `IQueryAssociations::GetString`.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_DropTarget">DropTarget</a></td><td>
For a verb invoked through COM and the `IDropTarget` interface, you can use this flag to retrieve the `IDropTarget` object's CLSID. 

 This CLSID is registered in the DropTarget subkey. The verb is specified in the `pwszExtra` parameter in the call to `IQueryAssociations::GetString`.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_Executable">Executable</a></td><td>
Gets an executable from a Shell verb command string. 

 For example, this string is found as the (Default) value for a subkey such as HKEY_CLASSES_ROOT\ApplicationName\shell\Open\command.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_FriendlyAppName">FriendlyAppName</a></td><td>
Gets the friendly name of an executable file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_FriendlyDocName">FriendlyDocName</a></td><td>
Gets the friendly name of a document type.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_InfoTip">InfoTip</a></td><td>
Corresponds to the InfoTip registry value. 

 Gets an info tip for an item, or list of properties in the form of an `IPropertyDescriptionList` from which to create an info tip, such as when hovering the cursor over a file name. 

 The list of properties can be parsed with `PSGetPropertyDescriptionListFromString`.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_Name">Name</a></td><td>
Gets the file extension name.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_NoOpen">NoOpen</a></td><td>
Gets a value indicating whether the association ignores the information associated with the 'open' subkey command.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_QuickTip">QuickTip</a></td><td>
Corresponds to the QuickTip registry value. Same as <a href="P_DevCase_Core_Shell_FileExtensionInfo_InfoTip">InfoTip</a>, except that it always returns a list of property names in the form of an `IPropertyDescriptionList`. 

 The difference between this value and <a href="P_DevCase_Core_Shell_FileExtensionInfo_InfoTip">InfoTip</a> is that this returns properties that are safe for any scenario that causes slow property retrieval, such as offline or slow networks. 

 Some of the properties returned from <a href="P_DevCase_Core_Shell_FileExtensionInfo_InfoTip">InfoTip</a> might not be appropriate for slow property retrieval scenarios. 

 The list of properties can be parsed with `PSGetPropertyDescriptionListFromString`.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_ShellExtension">ShellExtension</a></td><td>
For an object that has a Shell extension associated with it, you can use this to retrieve the CLSID of that Shell extension object.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_ShellNewValue">ShellNewValue</a></td><td>
Look under the ShellNew subkey.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_SupportedUriProtocols">SupportedUriProtocols</a></td><td>
(Introduced in Windows 8) 

 There is no official documentation for this member.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_FileExtensionInfo_TileInfo">TileInfo</a></td><td>
Corresponds to the TileInfo registry value. 

 Contains a list of properties to be displayed for a particular file type in a Windows Explorer window that is in tile view. 

 This is the same as <a href="P_DevCase_Core_Shell_FileExtensionInfo_InfoTip">InfoTip</a>, but, like <a href="P_DevCase_Core_Shell_FileExtensionInfo_QuickTip">QuickTip</a>, it also returns a list of property names in the form of an `IPropertyDescriptionList`. 

 The list of properties can be parsed with `PSGetPropertyDescriptionListFromString`</td></tr></table>&nbsp;
<a href="#fileextensioninfo-properties">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_FileExtensionInfo">FileExtensionInfo Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />