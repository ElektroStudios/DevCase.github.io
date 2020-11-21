# NativeMethods.SubtractRect Method 
 


## Overload List
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SubtractRect_1">SubtractRect(Rectangle, Rectangle, Rectangle)</a></td><td>
Determines the coordinates of a Rectangle formed by subtracting one Rectangle from another. 

 The function only subtracts the Rectangle specified by *refSrcRect2* from the Rectangle specified by *refSrcRect1* when the rectangles intersect completely in either the x- or y- direction. 

 For example, if *refSrcRect1* has the coordinates {10, 10, 100, 100} and *refSrcRect2* has the coordinates {50, 50, 150, 150}, the function sets the coordinates of the Rectangle pointed to by *refDstRect* to {10, 10, 100, 100}. 

 If *refSrcRect1* has the coordinates {10, 10, 100, 100} and *refSrcRect2* has the coordinates {50, 10, 150, 150}, however, the function sets the coordinates of the Rectangle pointed to by *refDstRect* to {10, 10, 50, 100}. 

 In other words, the resulting Rectangle is the bounding box of the geometric difference.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SubtractRect">SubtractRect(NativeRectangle, NativeRectangle, NativeRectangle)</a></td><td>
Determines the coordinates of a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> formed by subtracting one <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> from another. 

 The function only subtracts the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> specified by *refSrcRect2* from the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> specified by *refSrcRect1* when the rectangles intersect completely in either the x- or y- direction. 

 For example, if *refSrcRect1* has the coordinates {10, 10, 100, 100} and *refSrcRect2* has the coordinates {50, 50, 150, 150}, the function sets the coordinates of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> pointed to by *refDstRect* to {10, 10, 100, 100}. 

 If *refSrcRect1* has the coordinates {10, 10, 100, 100} and *refSrcRect2* has the coordinates {50, 10, 150, 150}, however, the function sets the coordinates of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> pointed to by *refDstRect* to {10, 10, 50, 100}. 

 In other words, the resulting <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> is the bounding box of the geometric difference.</td></tr></table>&nbsp;
<a href="#nativemethods.subtractrect-method">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />