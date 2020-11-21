# NativeUtil.SafePInvoke Method 
 


## Overload List
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_SafePInvoke__1">SafePInvoke(T)(Expression(Func(T)), Boolean)</a></td><td>
Invokes a platform invoke encapsulated function, providing a higher safety level for error-handling. 

 If the function that was called using platform invoke has the SetLastError, then it checks the exit code returned by the function, and, if is not same as *successValue*, throws the corresponding Win32Exception.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_SafePInvoke__1_1">SafePInvoke(T)(Expression(Func(T)), Int32)</a></td><td>
Invokes a platform invoke encapsulated function, providing a higher safety level for error-handling. 

 If the function that was called using platform invoke has the SetLastError, then it checks the exit code returned by the function, and, if is not same as *successValue*, throws the corresponding Win32Exception.</td></tr></table>&nbsp;
<a href="#nativeutil.safepinvoke-method">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />