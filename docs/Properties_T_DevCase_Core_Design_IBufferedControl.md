# IBufferedControl Properties
 

The <a href="T_DevCase_Core_Design_IBufferedControl">IBufferedControl</a> type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Design_IBufferedControl_DoubleBuffered">DoubleBuffered</a></td><td>
Gets or sets a value indicating whether this control should redraw its surface using a secondary buffer to reduce or prevent flicker.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Design_IBufferedControl_PreventFlickering">PreventFlickering</a></td><td>
Gets or sets a value that indicates whether the control should avoid unwanted flickering effects. 

 If `true` (`True` in Visual Basic), this will avoid any flickering effect on the control, however, it will also have a negative impact by slowing down the responsiveness of the control about to 30% slower. 

 This negative impact doesn't affect to the performance of the application itself, just to the performance of this control.</td></tr></table>&nbsp;
<a href="#ibufferedcontrol-properties">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Design_IBufferedControl">IBufferedControl Interface</a><br /><a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />