# GraphicalUtil Methods
 

The <a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil</a> type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_ActivateFullscreen">ActivateFullscreen</a></td><td>
Cause the specified Form to enter in Fullscreen mode.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_AllocateConsole">AllocateConsole</a></td><td>
Allocates a new console for the calling process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_AnimateWindow">AnimateWindow</a></td><td>
Produces special effects when showing or hiding a window. 

 This doesn't show the window so make sure you call Show() or set Visible property to `true` (`True` in Visual Basic) after calling <a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_AnimateWindow">AnimateWindow(IWin32Window, Int32, WindowAnimation)</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_CenterToControl">CenterToControl</a></td><td>
Centers the bounds of a source Control to a target Control.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_CenterToScreen">CenterToScreen(Control)</a></td><td>
Centers the bounds of the specified Control (normally a Form) to the current screen.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_CenterToScreen_1">CenterToScreen(Control, Screen)</a></td><td>
Centers the bounds of the specified Control (normally a Form) to the target screen.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_ControlInvoke__1">ControlInvoke(T)</a></td><td>
Synchronouslly Executes an encapsulated method on the thread that owns the specified control. 

 This method avoids cross-threading exceptions.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_ControlInvokeAsync__1">ControlInvokeAsync(T)</a></td><td>
Asynchronously Executes an encapsulated method on the thread that owns the specified control. 

 This method avoids cross-threading exceptions.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_DeactivateFullscreen">DeactivateFullscreen</a></td><td>
Cause the specified Form to exit from Fullscreen mode.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_DoEventsSafe">DoEventsSafe</a></td><td>
Processes all Windows messages currently in the message queue of the GUI. 

 This method greatly boosts the performance of any application in difference to DoEvents() method. 

 When calling DoEvents() to make the UI responsive, it generally decreases application performance; 

 however, using this method, we make sure there is at least one input event (keyboard or mouse) that needs to be processed before internally calling DoEvents().</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_EnableDoubleBufferedOnControl__1">EnableDoubleBufferedOnControl(T)</a></td><td>
Enables double buffering on the specified control. 

 Double buffering indicates whether a control should redraw its surface using a secondary buffer to reduce or prevent flicker.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_Fade">Fade</a></td><td>
Fades in or fades out a Form.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_ForceMessageQueuePump">ForceMessageQueuePump</a></td><td>
This method allows the current thread to perform long-running operations while continuing to perform standard COM and SendMessage pumping. 

 Calling this method during a long-running operation will prevent the Managed Debugging Assistant (MDA) 'ContextSwitchDeadlock' error to occur while debugging your solution. 

 This error may occur when the thread that owns the destination context/apartment is processing a very long-running operation without pumping Windows messages for a specific period of time. 

 For example, you will use this method while performing a long-running operation with COM objects (eg. inside a "infinite" loop) that is blocking the UI thread, 

 so it is unabling the UI thread to pump window messages as they arrive, causing the 'ContextSwitchDeadlock' error to occur in the Visual Studio debugger after 60 seconds.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_GetControlFromPoint">GetControlFromPoint(Control)</a></td><td>
Gets the corresponding control (if any) that is over the specified mouse point.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_GetControlFromPoint_2">GetControlFromPoint(Form)</a></td><td>
Gets the corresponding control (if any) that is over the current mouse point.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_GetControlFromPoint_1">GetControlFromPoint(Control, Point)</a></td><td>
Gets the corresponding control (if any) that is over the specified mouse point.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_GetControlFromPoint_3">GetControlFromPoint(Form, Point)</a></td><td>
Gets the corresponding control (if any) that is over the specified point.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_GetNonClientAreaMargins">GetNonClientAreaMargins(Control)</a></td><td>
Gets the non-client area margins of a Control.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_GetNonClientAreaMargins_1">GetNonClientAreaMargins(Form)</a></td><td>
Gets the non-client area margins of a Form.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_GetNotifyIconHandle">GetNotifyIconHandle</a></td><td>
Gets the handle of the specified NotifyIcon.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_GetNotifyIconRect">GetNotifyIconRect</a></td><td>
Gets the screen coordinates of the bounding Rectangle of the specified NotifyIcon.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_IsFullscreen">IsFullscreen(Process)</a></td><td>
Determine whether the specified process is running in fullscreen mode.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_IsFullscreen_1">IsFullscreen(IntPtr)</a></td><td>
Determine whether the specified window is running in fullscreen mode.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_IsFullscreen_2">IsFullscreen(Form)</a></td><td>
Determine whether the specified form is running in fullscreen mode.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_LoadCursorFromFile">LoadCursorFromFile(FileInfo)</a></td><td>
Creates a Cursor based on a cursor file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_LoadCursorFromFile_1">LoadCursorFromFile(String)</a></td><td>
Creates a Cursor based on a cursor file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_LoadCursorFromResource">LoadCursorFromResource</a></td><td>
Creates a Cursor based on the data contained in a managed .NET resource.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_MinimizeToSystray">MinimizeToSystray</a></td><td>
Minimizes the specified Form to system-tray.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_MouseIsOverControl">MouseIsOverControl</a></td><td>
Determinates whether the mouse pointer is inside the boundaries of a specified control.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_MoveToScreen">MoveToScreen</a></td><td>
Moves the specified Control (normally a Form) to the target screen.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_RestoreFromSystray">RestoreFromSystray</a></td><td>
Restores the visibility of the specified Form from system-tray.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_RoundBorders">RoundBorders(Control, Int32)</a></td><td>
Rounds the borders of a Control.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_RoundBorders_1">RoundBorders(Form, Int32)</a></td><td>
Rounds the borders of a Form. 

 Note that the FormBorderStyle form's property should be set to None.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_ShakeControl">ShakeControl</a></td><td>
Shakes the window of a Control during the specified amount of time.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_ShakeForm">ShakeForm</a></td><td>
Shakes the window of a Form during the specified amount of time.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_ShowSaveFileDialog">ShowSaveFileDialog</a></td><td>
Opens a SaveFileDialog dialog and returns the selected filepath.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_ToggleFormSystray">ToggleFormSystray</a></td><td>
Toggles the visibility of the specified Form to minimize it to system-tray or restore it from system-tray.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_ToggleFullscreen">ToggleFullscreen</a></td><td>
Toggles the Fullscreen mode of the specified Form.</td></tr></table>&nbsp;
<a href="#graphicalutil-methods">Back to Top</a>

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
<a href="#graphicalutil-methods">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />