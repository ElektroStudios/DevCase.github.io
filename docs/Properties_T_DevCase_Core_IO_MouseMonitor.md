# MouseMonitor Properties
 

The <a href="T_DevCase_Core_IO_MouseMonitor">MouseMonitor</a> type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseMonitor_DeviceCount">DeviceCount</a></td><td>
Gets the amount of mouse devices.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseMonitor_Enabled">Enabled</a></td><td>
Gets or sets a value that determines whether the mouselogger is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseMonitor_Handle">Handle</a></td><td>
Gets the handle for the window that owns this <a href="T_DevCase_Core_IO_MouseMonitor">MouseMonitor</a> instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseMonitor_OwnerWindow">OwnerWindow</a></td><td>
Gets the window that owns this <a href="T_DevCase_Core_IO_MouseMonitor">MouseMonitor</a> instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseMonitor_SuppressMouseButtonUpEventWhenDoubleClick">SuppressMouseButtonUpEventWhenDoubleClick</a></td><td>
** ONLY FOR TESTING PURPOSES ** 

 Gets or sets a value indicating whether to suppress the last `MouseUp` event of when a double-click occurs. 

 If this value is set to `true` (`True` in Visual Basic), the application will send the events in this order for a Double-Click: 

`MouseDown`, `MouseUp`, `MouseDown`, `MouseDoubleClick`

 If this value is set to `false` (`False` in Visual Basic), the application will send the events in this order for a Double-Click: `MouseDown`, `MouseUp`, `MouseDown`, `MouseUp`, `MouseDoubleClick`</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseMonitor_WorkingArea">WorkingArea</a></td><td>
Gets or sets the screen's working area on which to notify about mouse events. 

 The events fired by this <a href="T_DevCase_Core_IO_MouseMonitor">MouseMonitor</a> will be restricted to the bounds of the specified rectangle.</td></tr></table>&nbsp;
<a href="#mousemonitor-properties">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MouseMonitor">MouseMonitor Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />