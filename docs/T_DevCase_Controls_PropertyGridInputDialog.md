# PropertyGridInputDialog Class
 

Displays a dialog window with a property grid control to show and edit the properties of the specified object.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Component<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.CommonDialog<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Controls.PropertyGridInputDialog<br />
**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ToolboxBitmapAttribute(typeof(CommonDialog), "CommonDialog.bmp")]
[DefaultPropertyAttribute("SelectedObject")]
public class PropertyGridInputDialog : CommonDialog
```

**VB**<br />
``` VB
<ToolboxBitmapAttribute(GetType(CommonDialog), "CommonDialog.bmp")>
<DefaultPropertyAttribute("SelectedObject")>
Public Class PropertyGridInputDialog
	Inherits CommonDialog
```

**VB Usage**<br />
``` VB Usage
Dim instance As PropertyGridInputDialog
```

**C++**<br />
``` C++
[ToolboxBitmapAttribute(typeof(CommonDialog), L"CommonDialog.bmp")]
[DefaultPropertyAttribute(L"SelectedObject")]
public ref class PropertyGridInputDialog : public CommonDialog
```

**F#**<br />
``` F#
[<ToolboxBitmapAttribute(typeof(CommonDialog), "CommonDialog.bmp")>]
[<DefaultPropertyAttribute("SelectedObject")>]
type PropertyGridInputDialog =  
    class
        inherit CommonDialog
    end
```

The PropertyGridInputDialog type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_PropertyGridInputDialog__ctor">PropertyGridInputDialog</a></td><td>
Initializes a new instance of the PropertyGridInputDialog class.</td></tr></table>&nbsp;
<a href="#propertygridinputdialog-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_PropertyGridInputDialog_CommandsVisibleIfAvailable">CommandsVisibleIfAvailable</a></td><td>
Gets or sets a value indicating whether the commands pane is visible for objects that expose verbs.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_PropertyGridInputDialog_Font">Font</a></td><td>
Gets or sets the property grid font.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_PropertyGridInputDialog_HelpVisible">HelpVisible</a></td><td>
Gets or sets a value indicating whether the Help text is visible.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_PropertyGridInputDialog_LargeButtons">LargeButtons</a></td><td>
Gets or sets a value indicating whether buttons appear in standard size or in large size.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_PropertyGridInputDialog_MaximumSize">MaximumSize</a></td><td>
Gets or sets the maximum size for the dialog window.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_PropertyGridInputDialog_MinimumSize">MinimumSize</a></td><td>
Gets or sets the minimum size for the dialog window.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_PropertyGridInputDialog_PropertySort">PropertySort</a></td><td>
Gets or sets the type of sorting the property grid uses to display properties.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_PropertyGridInputDialog_Size">Size</a></td><td>
Gets or sets the desired size for the dialog window.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_PropertyGridInputDialog_Title">Title</a></td><td>
Gets or sets the dialog window title.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_PropertyGridInputDialog_ToolbarVisible">ToolbarVisible</a></td><td>
Gets or sets a value indicating whether the toolbar is visible.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_PropertyGridInputDialog_VisualStyle">VisualStyle</a></td><td>
Gets or sets the visual style.</td></tr></table>&nbsp;
<a href="#propertygridinputdialog-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_PropertyGridInputDialog_Reset">Reset</a></td><td>
Resets the properties of this dialog box to their default values.
 (Overrides CommonDialog.Reset().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_PropertyGridInputDialog_ShowDialog">ShowDialog()</a></td><td>
Runs this dialog box with a default owner.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_PropertyGridInputDialog_ShowDialog_1">ShowDialog(IWin32Window)</a></td><td>
Runs this dialog box with the specified owner.</td></tr></table>&nbsp;
<a href="#propertygridinputdialog-class">Back to Top</a>

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
<a href="#propertygridinputdialog-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />System.Windows.Forms.CommonDialog<br />