# VMWareVirtualMachine Properties
 

The <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">VMWareVirtualMachine</a> type exposes the following members.


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
<a href="#vmwarevirtualmachine-properties">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">VMWareVirtualMachine Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />