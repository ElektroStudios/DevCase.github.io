# OpenFileOrFolderDialog Class
 

Displays a dialog box that prompts the user to open a (single) file or folder.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Component<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.CommonDialog<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Controls.OpenFileOrFolderDialog<br />
**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ToolboxBitmapAttribute(typeof(Component), "Component.bmp")]
[DefaultEventAttribute("ItemOk")]
[DefaultPropertyAttribute("ItemName")]
public class OpenFileOrFolderDialog : CommonDialog
```

**VB**<br />
``` VB
<ToolboxBitmapAttribute(GetType(Component), "Component.bmp")>
<DefaultEventAttribute("ItemOk")>
<DefaultPropertyAttribute("ItemName")>
Public Class OpenFileOrFolderDialog
	Inherits CommonDialog
```

**VB Usage**<br />
``` VB Usage
Dim instance As OpenFileOrFolderDialog
```

**C++**<br />
``` C++
[ToolboxBitmapAttribute(typeof(Component), L"Component.bmp")]
[DefaultEventAttribute(L"ItemOk")]
[DefaultPropertyAttribute(L"ItemName")]
public ref class OpenFileOrFolderDialog : public CommonDialog
```

**F#**<br />
``` F#
[<ToolboxBitmapAttribute(typeof(Component), "Component.bmp")>]
[<DefaultEventAttribute("ItemOk")>]
[<DefaultPropertyAttribute("ItemName")>]
type OpenFileOrFolderDialog =  
    class
        inherit CommonDialog
    end
```

The OpenFileOrFolderDialog type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_OpenFileOrFolderDialog__ctor">OpenFileOrFolderDialog</a></td><td>
Initializes a new instance of the OpenFileOrFolderDialog class.</td></tr></table>&nbsp;
<a href="#openfileorfolderdialog-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_OpenFileOrFolderDialog_AutoUpgradeEnabled">AutoUpgradeEnabled</a></td><td>
Gets or sets a value indicating whether this dialog box should automatically upgrade appearance and behavior when running on Windows Vista.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_OpenFileOrFolderDialog_DereferenceLinks">DereferenceLinks</a></td><td>
Gets or sets a value indicating whether the dialog box returns the location of the file referenced by the shortcut or whether it returns the location of the shortcut (.lnk).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_OpenFileOrFolderDialog_InitialDirectory">InitialDirectory</a></td><td>
Gets or sets the initial directory displayed by the dialog box.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_OpenFileOrFolderDialog_ItemName">ItemName</a></td><td>
Gets or sets a string containing the name of the item selected in the dialog box.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_OpenFileOrFolderDialog_RestoreDirectory">RestoreDirectory</a></td><td>
Gets or sets a value indicating whether the dialog box restores the directory to the previously selected directory before closing.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_OpenFileOrFolderDialog_ShowHelp">ShowHelp</a></td><td>
Gets or sets a value indicating whether the Help button is displayed in the dialog box.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_OpenFileOrFolderDialog_Title">Title</a></td><td>
Gets or sets the dialog box title.</td></tr></table>&nbsp;
<a href="#openfileorfolderdialog-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_OpenFileOrFolderDialog_Reset">Reset</a></td><td>
Resets the properties of a common dialog box to their default values.
 (Overrides CommonDialog.Reset().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_OpenFileOrFolderDialog_ShowDialog">ShowDialog()</a></td><td>
Runs a common dialog box with a default owner.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_OpenFileOrFolderDialog_ShowDialog_1">ShowDialog(IWin32Window)</a></td><td>
Runs a common dialog box with a default owner.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_OpenFileOrFolderDialog_ToString">ToString</a></td><td>
Returns a string version of this object.
 (Overrides Component.ToString().)</td></tr></table>&nbsp;
<a href="#openfileorfolderdialog-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Controls_OpenFileOrFolderDialog_ItemOk">ItemOk</a></td><td>
Occurs when the user clicks on the Open button on the dialog box to select a file or folder.</td></tr></table>&nbsp;
<a href="#openfileorfolderdialog-class">Back to Top</a>

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
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Component_ComponentExtensions_GetEventHandlers">GetEventHandlers</a></td><td>
Gets all the delegates associated to the specified event raised by the source Component.
 (Defined by <a href="T_DevCase_Core_Extensions_Component_ComponentExtensions">ComponentExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#openfileorfolderdialog-class">Back to Top</a>

## Remarks
Original source-code: 

<a href="https://www.codeproject.com/Articles/44914/Select-file-or-folder-from-the-same-dialog" target="_blank">https://www.codeproject.com/Articles/44914/Select-file-or-folder-from-the-same-dialog</a>

## See Also


#### Reference
<a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />System.Windows.Forms.CommonDialog<br />