# ResourceUtil.ExecuteSafe Method 
 


## Overload List
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Data_Tools_ResourceUtil_ExecuteSafe">ExecuteSafe(Byte[])</a></td><td>
Loads a resource in memory and executes its main entrypoint. 

 The resource must be a .NET assembly. 

 If the loaded assembly attempts to force an application termination by for example internaly calling Exit(Int32), then the call is catched and ignored. 

 The downside is that the loaded assembly will not be able to call (P/Invoke) unmanaged code. You are advised. 

 *** Note that this is a experimental methodology. ***</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Data_Tools_ResourceUtil_ExecuteSafe_1">ExecuteSafe(Byte[], Object[])</a></td><td>
Loads a resource in memory and executes its main entrypoint. 

 The resource must be a .NET assembly. 

 If the loaded assembly attempts to force an application termination by for example internaly calling Exit(Int32), then the call is catched and ignored. 

 The downside is that the loaded assembly will not be able to call (P/Invoke) unmanaged code. You are advised. 

 *** Note that this is a experimental methodology. ***</td></tr></table>&nbsp;
<a href="#resourceutil.executesafe-method">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_ResourceUtil">ResourceUtil Class</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />