# RecycleBinUtil Class
 

Manages the system's Recycle Bins.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.WindowsAPICodePack.RecycleBinUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_WindowsAPICodePack">DevCase.ThirdParty.WindowsAPICodePack</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class RecycleBinUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class RecycleBinUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As RecycleBinUtil
```

**C++**<br />
``` C++
public ref class RecycleBinUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type RecycleBinUtil =  
    class
        inherit AestheticObject
    end
```

The RecycleBinUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil_MasterBin">MasterBin</a></td><td>
Gets the master recycle bin representation. The master Recycle Bin is the one that contains all the recycled items of all the recycle bins.</td></tr></table>&nbsp;
<a href="#recyclebinutil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil_Clean">Clean</a></td><td>
Cleans the Recycle Bin of an specific Drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil_DeleteItem">DeleteItem</a></td><td>
Permanently deletes a recycled Item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil_GetBinSize">GetBinSize</a></td><td>
Gets the accumulated size (in bytes) of the recycle bin of an specific drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil_GetItemsCount">GetItemsCount</a></td><td>
Gets the count of the items that are inside the recycle bin of an specific drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil_GetLastRecycledFile">GetLastRecycledFile</a></td><td>
Gets the last recycled file that is inside the recycle bin of an specific drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil_GetLastRecycledFolder">GetLastRecycledFolder</a></td><td>
Gets the last recycled folder that is inside the recycle bin of an specific drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil_GetLastRecycledItem">GetLastRecycledItem</a></td><td>
Gets the last recycled item that is inside the recycle bin of an specific drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil_GetRecycledFiles">GetRecycledFiles</a></td><td>
Gets all the recycled files that are inside the recycle bin of an specific drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil_GetRecycledFolders">GetRecycledFolders</a></td><td>
Gets all the recycled folders that are inside the recycle bin of an specific drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil_GetRecycledItems">GetRecycledItems</a></td><td>
Gets all the recycled items that are inside the recycle bin of an specific drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil_InvokeItemVerb">InvokeItemVerb(ShellObject, ItemVerbs)</a></td><td>
Invokes a verb on a ShellObject item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil_InvokeItemVerb_1">InvokeItemVerb(ShellObject, String)</a></td><td>
Invokes a custom verb on a ShellObject item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil_UndeleteItem">UndeleteItem</a></td><td>
Undeletes a recycled Item.</td></tr></table>&nbsp;
<a href="#recyclebinutil-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#recyclebinutil-class">Back to Top</a>

## Examples
This is a code example that demonstrates how to loop through recycled items. 
**VB**<br />
``` VB
Private Sub Test()

    Dim sb As New Global.System.Text.StringBuilder

    ' Get all the deleted items inside all the Recycle Bins.
    Dim recycledItems As IEnumerable(Of ShellObject) = RecycleBin.MasterBin.Items

    ' Loop through the deleted Items (Ordered by las deleted).
    For Each item As ShellObject In (From itm In recycledItems
                                   Order By itm.Properties.GetProperty("System.Recycle.DateDeleted").ValueAsObject
                                   Descending)

        ' Append the property bags information.
        With sb
            .AppendLine(String.Format("Full Name....: {0}", item.Name))
            .AppendLine(String.Format("Item Name....: {0}", item.Properties.System.FileName.Value))
            .AppendLine(String.Format("Deleted From.: {0}", item.Properties.GetProperty("System.Recycle.DeletedFrom").ValueAsObject))
            .AppendLine(String.Format("Item Type....: {0}", item.Properties.System.ItemTypeText.Value))
            .AppendLine(String.Format("Item Size....: {0}", CStr(item.Properties.System.Size.Value)))
            .AppendLine(String.Format("Attributes...: {0}", [Enum].Parse(GetType(IO.FileAttributes), item.Properties.System.FileAttributes.Value.ToString())))
            .AppendLine(String.Format("Date Deleted.: {0}", item.Properties.GetProperty("System.Recycle.DateDeleted").ValueAsObject))
            .AppendLine(String.Format("Date Modified: {0}", CStr(item.Properties.System.DateModified.Value)))
            .AppendLine(String.Format("Date Created.: {0}", CStr(item.Properties.System.DateCreated.Value)))
        End With

        MessageBox.Show(sb.ToString())
        sb.Clear()

    Next item

End Sub
```


## Examples
This is a code example that demonstrates general usage of this class. 
**VB**<br />
``` VB
' Clean all the Recycle Bins.
RecycleBin.MasterBin.Clean()

' Clean the Recycle Bin of the "E" drive.
RecycleBin.Clean("E"c, RecycleFlags.DontShowConfirmation)

' Update the icon of the master Recycle Bin (on desktop).
RecycleBin.MasterBin.UpdateIcon()

' Get the accumulated size (in bytes) of the master Recycle Bin.
Dim binSize As Long = RecycleBin.MasterBin.Size
Console.WriteLine(String.Format("Bin Size: {0}", binSize))

' Get the recycled item count of the master recycle bin.
Dim binItemCount As Long = RecycleBin.MasterBin.ItemsCount
Console.WriteLine(String.Format("item count: {0}", binItemCount))

' Get all the recycled items of the master Recycle Bin.
Dim binItems As IEnumerable(Of ShellObject) = RecycleBin.MasterBin.Items
Console.WriteLine(String.Format("Items: {0}", String.Join(Environment.NewLine, binItems)))

' Get all the recycled files of the master Recycle Bin.
Dim binFiles As IEnumerable(Of ShellFile) = RecycleBin.MasterBin.Files

' Get all the recycled folders of the master Recycle Bin.
Dim binFolders As IEnumerable(Of ShellFolder) = RecycleBin.MasterBin.Folders

' Get all the recycled items of the Recycle Bin on "E" drive.
Dim binItemsE As IEnumerable(Of ShellObject) = RecycleBin.GetRecycledItems("E"c)

' Get all the recycled files of the Recycle Bin on "E" drive.
Dim binFilesE As IEnumerable(Of ShellFile) = RecycleBin.GetRecycledFiles("E"c)

' Get all the recycled folders of the Recycle Bin on "E" drive.
Dim binFoldersE As IEnumerable(Of ShellFolder) = RecycleBin.GetRecycledFolders("E"c)

' Gets the Last recycled item in the master Recycle Bin.
MsgBox(RecycleBin.MasterBin.LastRecycledItem.Name)

' Gets the Last recycled item in the Recycle Bin on "E" drive
MsgBox(RecycleBin.GetLastRecycledItem("E"c).Name)

' Undeletes an item.
RecycleBin.UndeleteItem(RecycleBin.MasterBin.LastRecycledItem)

' Permanently deletes an item.
RecycleBin.DeleteItem(RecycleBin.MasterBin.LastRecycledItem)

' Invokes an Item verb
RecycleBin.InvokeItemVerb(RecycleBin.MasterBin.LastRecycledItem, ItemVerbs.Properties)

' Invokes a custom item verb
RecycleBin.InvokeItemVerb(RecycleBin.MasterBin.LastRecycledItem, "play")
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_WindowsAPICodePack">DevCase.ThirdParty.WindowsAPICodePack Namespace</a><br />