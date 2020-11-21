# LowMemoryNotificationContext Class
 

A class that periodically checks the total amount of free physical memory for the computer, and, in the case of the total amount of free physical memory is lower than the value specified in <a href="P_DevCase_Core_IO_LowMemoryNotificationContext_Minimum">Minimum</a>, the Action specified in <a href="P_DevCase_Core_IO_LowMemoryNotificationContext_Action">Action</a> will be invoked once.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.LowMemoryNotificationContext<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class LowMemoryNotificationContext : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class LowMemoryNotificationContext
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As LowMemoryNotificationContext
```

**C++**<br />
``` C++
public ref class LowMemoryNotificationContext sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type LowMemoryNotificationContext =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The LowMemoryNotificationContext type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_LowMemoryNotificationContext__ctor">LowMemoryNotificationContext</a></td><td>
Initializes a new instance of the LowMemoryNotificationContext class.</td></tr></table>&nbsp;
<a href="#lowmemorynotificationcontext-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_LowMemoryNotificationContext_Action">Action</a></td><td>
Gets the Action to invoke once if a low-memory notification occurs.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_LowMemoryNotificationContext_Minimum">Minimum</a></td><td>
Gets or sets the minimum required memory, in bytes. 

 If the total amount of free physical memory for the computer is lower than this value, the Action specified in <a href="P_DevCase_Core_IO_LowMemoryNotificationContext_Action">Action</a> will be invoked once.</td></tr></table>&nbsp;
<a href="#lowmemorynotificationcontext-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_LowMemoryNotificationContext_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr></table>&nbsp;
<a href="#lowmemorynotificationcontext-class">Back to Top</a>

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
<a href="#lowmemorynotificationcontext-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
<ReliabilityContract(Consistency.WillNotCorruptState, Cer.MayFail)>
<SecurityCritical>
Private Sub Test() 

    Dim computerInfo As New Microsoft.VisualBasic.Devices.ComputerInfo()
    Dim minMemory As ULong = 1073741824 '1 GB
    Dim action As New Action(
        Sub()
            Console.WriteLine("Available free physical memory is running low...")
            Console.WriteLine($"Total...........: {New Filesize(computerInfo.TotalPhysicalMemory, SizeUnits.Byte)}")
            Console.WriteLine($"Available.......: {New Filesize(computerInfo.AvailablePhysicalMemory, SizeUnits.Byte)}")
            Console.WriteLine($"Minimum required: {New Filesize(minMemory, SizeUnits.Byte)}")
        End Sub)

    Using lowMemNotify As New LowMemoryNotificationContext(minMemory, action, 1000)

        ' Allocate all available physical memory:
        Dim allocSize As New IntPtr(CLng(computerInfo.AvailablePhysicalMemory))
        Dim alloc As IntPtr = Marshal.AllocHGlobal(allocSize)
        NativeMethods.ZeroMemory(alloc, allocSize)

        ' Run job until the low-memory notification occurs.
        Do While True
            Thread.Sleep(100)
            Application.DoEvents()
        Loop

    End Using

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />