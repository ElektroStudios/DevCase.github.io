# DevProgressDialog Class
 

Represents a system progress dialog. 

 This control is a generic way to show a user how an operation is progressing. 

 It is typically used when deleting, uploading, copying, moving, or downloading large numbers of files. 

 The dialog is shown on a separate thread and will not block operations in the current thread.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Component<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Controls.DevProgressDialog<br />
**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ToolboxBitmapAttribute(typeof(Component), "Component.bmp")]
[DefaultPropertyAttribute("Title")]
public class DevProgressDialog : Component
```

**VB**<br />
``` VB
<ToolboxBitmapAttribute(GetType(Component), "Component.bmp")>
<DefaultPropertyAttribute("Title")>
Public Class DevProgressDialog
	Inherits Component
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevProgressDialog
```

**C++**<br />
``` C++
[ToolboxBitmapAttribute(typeof(Component), L"Component.bmp")]
[DefaultPropertyAttribute(L"Title")]
public ref class DevProgressDialog : public Component
```

**F#**<br />
``` F#
[<ToolboxBitmapAttribute(typeof(Component), "Component.bmp")>]
[<DefaultPropertyAttribute("Title")>]
type DevProgressDialog =  
    class
        inherit Component
    end
```

The DevProgressDialog type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevProgressDialog__ctor">DevProgressDialog</a></td><td>
Initializes a new instance of the DevProgressDialog class.</td></tr></table>&nbsp;
<a href="#devprogressdialog-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressDialog_AutoTimeEstimation">AutoTimeEstimation</a></td><td>
Gets or sets a value indicating whether to automatically estimate the remaining time and display it.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressDialog_CancelMessage">CancelMessage</a></td><td>
Gets or sets a message to be displayed if the user cancels the operation.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressDialog_CompactStrings">CompactStrings</a></td><td>
Gets or sets a value indicating whether to compact displayed strings if they are too large to fit on a line.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressDialog_Description">Description</a></td><td>
Gets or sets the description that appears on the first line.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressDialog_Detail">Detail</a></td><td>
Gets or sets the detail that appears on the second line.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressDialog_HideTimeRemaining">HideTimeRemaining</a></td><td>
Gets or sets a value indicating whether to show the "time remaining" text.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressDialog_MinimizeBox">MinimizeBox</a></td><td>
Gets or sets a value indicating whether the Minimize button is displayed in the caption bar of the progress dialog.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressDialog_Modal">Modal</a></td><td>
Gets a value indicating whether this form is displayed modally.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressDialog_ShowCancelButton">ShowCancelButton</a></td><td>
Gets or sets a value indicating whether a Cancel button is displayed on the progress dialog.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressDialog_Style">Style</a></td><td>
Gets or sets the style of the progress bar on the progress dialog.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressDialog_Title">Title</a></td><td>
Gets or sets the progress dialog box title.</td></tr></table>&nbsp;
<a href="#devprogressdialog-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevProgressDialog_Start">Start</a></td><td>
Starts the progress dialog box.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevProgressDialog_Stop">Stop</a></td><td>
Stops the progress dialog box and removes it from the screen.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevProgressDialog_UpdateProgress">UpdateProgress</a></td><td>
Updates the progress dialog box with the current state of the operation.</td></tr></table>&nbsp;
<a href="#devprogressdialog-class">Back to Top</a>

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
<a href="#devprogressdialog-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dlg As New DevProgressDialog With {
    .Title = "Title",
    .Description = "Description",
    .Detail = "Detail...",
    .CancelMessage = "Canceling. Please wait...",
    .AutoTimeEstimation = True,
    .CompactStrings = True,
    .HideTimeRemaining = False,
    .MinimizeBox = True,
    .Modal = True,
    .ShowCancelButton = True,
    .Style = DevProgressDialogStyle.Normal
}

Dim window As IWin32Window = Me
dlg.Start(window)

Dim current As ULong = 0
Dim total As ULong = 100

For i As ULong = 0 To total
    If (dlg.IsCancelled) Then
        Exit For
    End If

    Thread.Sleep(100)
    dlg.UpdateProgress(i, total)
    Application.DoEvents()

Next

dlg.Stop()
```


## See Also


#### Reference
<a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />