# VMWareVirtualMachine Class
 

Represents a VMWare Virtual Machine.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.VmWare.VMWareVirtualMachine<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class VMWareVirtualMachine : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class VMWareVirtualMachine
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As VMWareVirtualMachine
```

**C++**<br />
``` C++
public ref class VMWareVirtualMachine sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type VMWareVirtualMachine =  
    class
        inherit AestheticObject
    end
```

The VMWareVirtualMachine type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VMWareVirtualMachine__ctor">VMWareVirtualMachine</a></td><td>
Initializes a new instance of the VMWareVirtualMachine class.</td></tr></table>&nbsp;
<a href="#vmwarevirtualmachine-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_BiosUuId">BiosUuId</a></td><td>
Gets the BIOS UUID.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_CoresPerProcessor">CoresPerProcessor</a></td><td>
Gets the amount of cores per processor of this VM.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_DisplayName">DisplayName</a></td><td>
Gets the display name of this VM.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_Firmware">Firmware</a></td><td>
Gets the firmware type of this VM. It can be: BIOS, or UEFI.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_GraphicsHardwareAccelerationEnabled">GraphicsHardwareAccelerationEnabled</a></td><td>
Gets a value that determine whether 3D graphics hardware acceleration is enabled in this VM.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_GraphicsMemorySize">GraphicsMemorySize</a></td><td>
Gets the total graphics memory size of this VM, in megabytes.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_GuestOsCredential">GuestOsCredential</a></td><td>
Gets or sets the username and password of the running user-account in the guest operating system of this VM. 

 The credential is required to perform some I/O operations with VMWare's vmrun.exe program. So you must set this credential before using vmrun.exe.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_IsSharedVm">IsSharedVm</a></td><td>
Gets a value that determine whether this VM is a shared VM.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_MemorySize">MemorySize</a></td><td>
Gets the total memory size of this VM, in megabytes.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_OsVersion">OsVersion</a></td><td>
Gets the version of the guest operating system of this VM.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_ProcessorCount">ProcessorCount</a></td><td>
Gets the amount of processors of this VM. 

 The resulting value is the division between <a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_TotalProcessorCores">TotalProcessorCores</a> \ <a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_CoresPerProcessor">CoresPerProcessor</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_SecureBootEnabled">SecureBootEnabled</a></td><td>
Gets a value that determine whether secureboot is enabled for UEFI firmware mode.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_SharedFolders">SharedFolders</a></td><td>
Gets the shared folders of this VM.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_TotalProcessorCores">TotalProcessorCores</a></td><td>
Gets the amount of processor cores of this VM.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_VmGenerationId">VmGenerationId</a></td><td>
Gets the VM-Generation ID.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_VmHardwareVersion">VmHardwareVersion</a></td><td>
Gets the hardware version of this VM.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_VmxFile">VmxFile</a></td><td>
Gets .vmx file of this VM.</td></tr></table>&nbsp;
<a href="#vmwarevirtualmachine-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_Refresh">Refresh</a></td><td>
Refresh the state (the properties) of this VMWareVirtualMachine.</td></tr></table>&nbsp;
<a href="#vmwarevirtualmachine-class">Back to Top</a>

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
<a href="#vmwarevirtualmachine-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />