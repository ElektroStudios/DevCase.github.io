# SystemMenuManager Class
 

Manages the system menu of a window.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.NativeWindow<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticNativeWindow">DevCase.Core.Design.AestheticNativeWindow</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.SystemMenuManager<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class SystemMenuManager : AestheticNativeWindow, 
	IDisposable
```

**VB**<br />
``` VB
Public Class SystemMenuManager
	Inherits AestheticNativeWindow
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
```

**C++**<br />
``` C++
public ref class SystemMenuManager : public AestheticNativeWindow, 
	IDisposable
```

**F#**<br />
``` F#
type SystemMenuManager =  
    class
        inherit AestheticNativeWindow
        interface IDisposable
    end
```

The SystemMenuManager type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager__ctor">SystemMenuManager</a></td><td>
Initializes a new instance of the SystemMenuManager class.</td></tr></table>&nbsp;
<a href="#systemmenumanager-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_SystemMenuManager_Handle">Handle</a></td><td>
Gets the handle for the window that owns this SystemMenuManager instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_SystemMenuManager_MenuEnabled">MenuEnabled</a></td><td>
Gets or sets a value indicating whether the system menu of the window is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_SystemMenuManager_OwnerWindow">OwnerWindow</a></td><td>
Gets the window that owns this SystemMenuManager instance.</td></tr></table>&nbsp;
<a href="#systemmenumanager-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_AddItem">AddItem</a></td><td>
Adds an Item at the given position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_AddSeparator">AddSeparator</a></td><td>
Add a separator at given position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_ClearMenu">ClearMenu</a></td><td>
Removes all the menu items.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_GetItemBitmap_1">GetItemBitmap(Int32)</a></td><td>
Returns the custom Bitmap image used by a menu item at given position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_GetItemBitmap">GetItemBitmap(MenuItem)</a></td><td>
Returns the custom Bitmap image used by a menu item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_GetItemCount">GetItemCount</a></td><td>
Gets the amount of items in the system menu.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_GetItemID_1">GetItemID(Int32)</a></td><td>
Gets the Id of a menu item at given position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_GetItemID">GetItemID(MenuItem)</a></td><td>
Gets the Id of a menu item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_GetItemState_1">GetItemState(Int32)</a></td><td>
Gets the state of a menu item at given position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_GetItemState">GetItemState(MenuItem)</a></td><td>
Gets the state of a menu item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_GetItemText_1">GetItemText(Int32)</a></td><td>
Gets the text of a menu item at given position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_GetItemText">GetItemText(MenuItem)</a></td><td>
Gets the text of a menu item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_IsMenu">IsMenu</a></td><td>
Determines whether a handle is a menu handle.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_RemoveItemBitmap_1">RemoveItemBitmap(Int32)</a></td><td>
Removes the custom Bitmap image used by a menu item at given position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_RemoveItemBitmap">RemoveItemBitmap(MenuItem)</a></td><td>
Removes the custom Bitmap image used by a menu item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_RestoreMenu">RestoreMenu</a></td><td>
Restores the system menu to defaults.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_SetItemBitmap_1">SetItemBitmap(Int32, Bitmap)</a></td><td>
Set a custom Bitmap image for a menu item at given position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_SetItemBitmap">SetItemBitmap(MenuItem, Bitmap)</a></td><td>
Set a custom Bitmap image for a menu item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_SetItemState_1">SetItemState(Int32, MenuItemState)</a></td><td>
Set an state for a menu item at given position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_SetItemState">SetItemState(MenuItem, MenuItemState)</a></td><td>
Set an state for a menu item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_SetItemText_1">SetItemText(Int32, String)</a></td><td>
Set the text of a menu item at given position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_SetItemText">SetItemText(MenuItem, String)</a></td><td>
Set the text of a menu item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_SetMenuBackColor">SetMenuBackColor</a></td><td>
Set the background color of a menu.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_SystemMenuManager_SetMenuStyle">SetMenuStyle</a></td><td>
Set the menu style.</td></tr></table>&nbsp;
<a href="#systemmenumanager-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Application_UserInterface_SystemMenuManager_MenuItemClicked">MenuItemClicked</a></td><td>
Occurs when a menu item is clicked.</td></tr></table>&nbsp;
<a href="#systemmenumanager-class">Back to Top</a>

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
<a href="#systemmenumanager-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    Friend WithEvents SystemMenu As New Global.SystemMenuManager(Me)

    Private Shadows Sub Shown() Handles MyBase.Shown

        ' Disable the menu
        SystemMenu.MenuEnabled = False

        ' Enable the menu
        SystemMenu.MenuEnabled = True

        ' Gets the total amount of menu items.
        MsgBox(SystemMenu.GetItemCount())

        ' Sets the menu background color.
        SystemMenu.SetMenuBackColor(Color.Teal)

        ' Sets the menu style.
        SystemMenu.SetMenuStyle(MenuStyle.AutoDismis)

        ' Sets the state of the Close button and menu item.
        SystemMenu.SetItemState(MenuItem.Close, MenuItemState.Disabled)

        ' Sets the Bitmap image of the Move menu item.
        'SystemMenu.SetItemBitmap(MenuItem.Move, New Bitmap("C:\File.png"))

        ' Gets the Bitmap image of the Move menu item.
        Dim bmp As Bitmap = SystemMenu.GetItemBitmap(MenuItem.Move)

        ' Removes the Bitmap image of the Move menu item.
        SystemMenu.RemoveItemBitmap(MenuItem.Move)

        ' Gets the ID of an item.
        MsgBox(SystemMenu.GetItemState(MenuItem.Move).ToString())

        ' Gets the text of an item.
        MsgBox(SystemMenu.GetItemText(MenuItem.Move))

        ' Gets the state of an item.
        MsgBox(SystemMenu.GetItemState(MenuItem.Move).ToString())

        ' Sets the text of an item.
        SystemMenu.SetItemText(MenuItem.Move, "Muéveme")

        ' Checks if a handle is a menu handle.
        MsgBox(SystemMenuManager.IsMenu(IntPtr.Zero))

        ' Remove all the menu items.
        'SystemMenu.ClearMenu()

        ' Restore the menu to defaults.
        'SystemMenu.RestoreMenu()

        ' Dispose the SystemMenuManager Object.
        'SystemMenu.Dispose()

    End Sub

    Private Sub SystemMenu_MenuItemClicked(ByVal sender As Object, ByVal e As MenuItemClickedEventArgs) _
    Handles SystemMenu.MenuItemClicked

        Dim sb As New Global.System.Text.StringBuilder
        With sb
            .AppendLine(String.Format("Menu handle: {0}", DirectCast(sender, IntPtr).ToInt32()))
            .AppendLine(String.Format("Item ID    : {0}", CStr(e.Id)))
            .AppendLine(String.Format("Item Text  : {0}", e.Text))
            .AppendLine(String.Format("Item Type  : {0}", e.Type.ToString()))
            .AppendLine(String.Format("Item State : {0}", e.State.ToString()))
        End With

        Console.WriteLine(sb.ToString(), "SystemMenuManager", MessageBoxButtons.OK, MessageBoxIcon.Information)

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />