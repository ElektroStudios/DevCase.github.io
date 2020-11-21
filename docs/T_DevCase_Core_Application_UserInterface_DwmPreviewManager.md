# DwmPreviewManager Class
 

Manages the images that will be used to display a thumbnail preview or peek preview for the specified window.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.NativeWindow<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticNativeWindow">DevCase.Core.Design.AestheticNativeWindow</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.DwmPreviewManager<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class DwmPreviewManager : AestheticNativeWindow, 
	IDisposable
```

**VB**<br />
``` VB
Public Class DwmPreviewManager
	Inherits AestheticNativeWindow
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As DwmPreviewManager
```

**C++**<br />
``` C++
public ref class DwmPreviewManager : public AestheticNativeWindow, 
	IDisposable
```

**F#**<br />
``` F#
type DwmPreviewManager =  
    class
        inherit AestheticNativeWindow
        interface IDisposable
    end
```

The DwmPreviewManager type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DwmPreviewManager__ctor">DwmPreviewManager(IntPtr)</a></td><td>
Initializes a new instance of the DwmPreviewManager class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DwmPreviewManager__ctor_1">DwmPreviewManager(IWin32Window)</a></td><td>
Initializes a new instance of the DwmPreviewManager class.</td></tr></table>&nbsp;
<a href="#dwmpreviewmanager-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_DwmPreviewManager_Handle">Handle</a></td><td>
Gets the handle for the window that owns this DwmPreviewManager instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_DwmPreviewManager_OwnerWindow">OwnerWindow</a></td><td>
Gets the window that owns this DwmPreviewManager instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_DwmPreviewManager_PeekImage">PeekImage</a></td><td>
Gets or sets the image that will be used to display a peek preview of the current Window.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_DwmPreviewManager_ThumbnailImage">ThumbnailImage</a></td><td>
Gets or sets the image that will be used to display a thumbnail preview of the current Window.</td></tr></table>&nbsp;
<a href="#dwmpreviewmanager-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DwmPreviewManager_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr></table>&nbsp;
<a href="#dwmpreviewmanager-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Application_UserInterface_DwmPreviewManager_PeekPreviewRequested">PeekPreviewRequested</a></td><td>
Occurs when Windows requested to display a live (`Aero Peek`) preview on the Taskbar or window manager (`ALT+TAB`) menu.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Application_UserInterface_DwmPreviewManager_ThumbnailPreviewRequested">ThumbnailPreviewRequested</a></td><td>
Occurs when Windows requested to display a thumbnail preview on the Taskbar or window manager (`ALT+TAB`) menu.</td></tr></table>&nbsp;
<a href="#dwmpreviewmanager-class">Back to Top</a>

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
<a href="#dwmpreviewmanager-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Friend WithEvents DwmPreview As DwmPreviewManager

Private Sub Form1_Shown() Handles MyBase.Shown

    Me.DwmPreview = New DwmPreviewManager(Me)

    Using thumbnailImage As Bitmap = DirectCast(Bitmap.FromFile("C:\Image1.jpg"), Bitmap)
        Me.DwmPreview.ThumbnailImage = thumbnailImage
    End Using

    Using peekImage As Bitmap = DirectCast(Bitmap.FromFile("C:\Image2.jpg"), Bitmap)
        Me.DwmPreview.PeekImage = peekImage
    End Using

End Sub

Private Sub DwmPreview_ThumbnailPreviewRequested(ByVal sender As Object, ByVal e As EventArgs) _
Handles DwmPreview.ThumbnailPreviewRequested
    ' Do something here...
End Sub

Private Sub DwmPreview_PeekPreviewRequested(ByVal sender As Object, ByVal e As EventArgs) _
Handles DwmPreview.PeekPreviewRequested
    ' Do something here...
End Sub
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />