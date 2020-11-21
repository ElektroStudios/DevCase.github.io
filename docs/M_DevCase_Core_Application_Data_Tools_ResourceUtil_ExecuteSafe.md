# ResourceUtil.ExecuteSafe Method (Byte[])
 

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
	byte[] resource
)
```

**VB**<br />
``` VB
Public Shared Sub ExecuteSafe ( 
	resource As Byte()
)
```

**VB Usage**<br />
``` VB Usage
Dim resource As Byte()

ResourceUtil.ExecuteSafe(resource)
```

**C++**<br />
``` C++
public:
static void ExecuteSafe(
	array<unsigned char>^ resource
)
```

**F#**<br />
``` F#
static member ExecuteSafe : 
        resource : byte[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>resource</dt><dd>Type: System.Byte[]<br />The resource to execute.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>EntryPointNotFoundException</td><td>Entrypoint not found in the specified resource. Are you sure it is a .NET assembly?</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
ExecuteSafe(My.Resources.MyProgram)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_ResourceUtil">ResourceUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_ResourceUtil_ExecuteSafe">ExecuteSafe Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />