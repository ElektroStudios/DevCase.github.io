# ResourceUtil.ExecuteSafe Method (Byte[], Object[])
 

Loads a resource in memory and executes its main entrypoint. 

 The resource must be a .NET assembly. 

 If the loaded assembly attempts to force an application termination by for example internaly calling Exit(Int32), then the call is catched and ignored. 

 The downside is that the loaded assembly will not be able to call (P/Invoke) unmanaged code. You are advised. 

 *** Note that this is a experimental methodology. ***

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ExecuteSafe(
	byte[] resource,
	Object[] parameters
)
```

**VB**<br />
``` VB
Public Shared Sub ExecuteSafe ( 
	resource As Byte(),
	parameters As Object()
)
```

**VB Usage**<br />
``` VB Usage
Dim resource As Byte()
Dim parameters As Object()

ResourceUtil.ExecuteSafe(resource, parameters)
```

**C++**<br />
``` C++
public:
static void ExecuteSafe(
	array<unsigned char>^ resource, 
	array<Object^>^ parameters
)
```

**F#**<br />
``` F#
static member ExecuteSafe : 
        resource : byte[] * 
        parameters : Object[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>resource</dt><dd>Type: System.Byte[]<br />The resource to execute.</dd><dt>parameters</dt><dd>Type: System.Object[]<br />The parameters to pass to the method executed.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>EntryPointNotFoundException</td><td>Entrypoint not found in the specified resource. Are you sure it is a .NET assembly?</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
ExecuteSafe(My.Resources.MyProgram, {"Parameter 1", "Parameter 2", "etc..."})
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_ResourceUtil">ResourceUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_ResourceUtil_ExecuteSafe">ExecuteSafe Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />