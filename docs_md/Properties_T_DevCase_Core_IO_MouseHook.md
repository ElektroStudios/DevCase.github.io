# MouseHook Properties
 

The <a href="T_DevCase_Core_IO_MouseHook">MouseHook</a> type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseHook_IsEnabled">IsEnabled</a></td><td>
Gets a value indicating whether the Hook is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseHook_IsInstalled">IsInstalled</a></td><td>
Gets a value indicating whether the Hook is installed.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseHook_SuppressMouseButtonUpEventWhenDoubleClick">SuppressMouseButtonUpEventWhenDoubleClick</a></td><td>
** ONLY FOR TESTING PURPOSES ** 

 Gets or sets a value indicating whether to suppress the last `MouseUp` event of when a double-click occurs. 

 If this value is set to `true` (`True` in Visual Basic), the application will send the events in this order for a Double-Click: 

`MouseDown`, `MouseUp`, `MouseDown`, `MouseDoubleClick`

 If this value is set to `false` (`False` in Visual Basic), the application will send the events in this order for a Double-Click: `MouseDown`, `MouseUp`, `MouseDown`, `MouseUp`, `MouseDoubleClick`</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseHook_WorkingArea">WorkingArea</a></td><td>
Gets or sets the screen's working area on which to notify about mouse events. 

 The events fired by this mouseHook will be restricted to the bounds of the specified rectangle.</td></tr></table>&nbsp;
<a href="#mousehook-properties">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MouseHook">MouseHook Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />