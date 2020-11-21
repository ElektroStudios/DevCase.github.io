# VmRunWrapper Class
 

A wrapper of VmWare's vmrun.exe application.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.VmWare.VmRunWrapper<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class VmRunWrapper : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class VmRunWrapper
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
```

**C++**<br />
``` C++
public ref class VmRunWrapper sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type VmRunWrapper =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The VmRunWrapper type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper__ctor">VmRunWrapper</a></td><td>
Initializes a new instance of the VmRunWrapper class.</td></tr></table>&nbsp;
<a href="#vmrunwrapper-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VmRunWrapper_Exists">Exists</a></td><td>
Gets a value indicating whether the `VmRun.exe` file Exists.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VmRunWrapper_FilePath">FilePath</a></td><td>
Gets the `VmRun.exe` file path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VmWare_VmRunWrapper_Process">Process</a></td><td>
Gets the `VmRun.exe`Process instance.</td></tr></table>&nbsp;
<a href="#vmrunwrapper-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_CaptureScreen">CaptureScreen</a></td><td>
Capture the screen of the guest operating system of the specified virtual machine and save it to a image file (in .PNG format) in the host operating system.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_DirectoryCreate">DirectoryCreate</a></td><td>
Create a directory in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_DirectoryDelete">DirectoryDelete</a></td><td>
Delete a directory from the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_DirectoryExists">DirectoryExists</a></td><td>
Determine whether a directory exists in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_DirectoryExistsAsync">DirectoryExistsAsync</a></td><td>
Asynchronously determine whether a directory exists in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_FileCopyFromGuestToHost">FileCopyFromGuestToHost</a></td><td>
Copies a file from the guest operating system of the specified virtual machine to the host operating system.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_FileCopyFromHostToGuest">FileCopyFromHostToGuest</a></td><td>
Copies a file from the host operating system to the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_FileDelete">FileDelete</a></td><td>
Delete a file from the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_FileExists">FileExists</a></td><td>
Determine whether a file exists in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_FileExistsAsync">FileExistsAsync</a></td><td>
Asynchronously determine whether a file exists in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_FileRename">FileRename</a></td><td>
Rename a file in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_GetIpAddress">GetIpAddress</a></td><td>
Gets the IP address of the guest operating system on the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_GetIpAddressAsync">GetIpAddressAsync</a></td><td>
Asynchronously gets the IP address of the guest operating system on the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_GetRunningVmCount">GetRunningVmCount</a></td><td>
Gets the amount of virtual machines that are running on the host operating system.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_GetRunningVmCountAsync">GetRunningVmCountAsync</a></td><td>
Asynchronously gets the amount of virtual machines that are running on the host operating system.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_GetRunningVms">GetRunningVms</a></td><td>
Gets the file paths of the virtual machines that are running on the host operating system.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_GetRunningVmsAsync">GetRunningVmsAsync</a></td><td>
Asynchronously gets the file paths of the virtual machines that are running on the host operating system.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_GetSnapshotCount">GetSnapshotCount</a></td><td>
Gets the amount of snapshots created in the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_GetSnapshotCountAsync">GetSnapshotCountAsync</a></td><td>
Asynchronously gets the amount of snapshots created in the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_GetSnapshotNames">GetSnapshotNames</a></td><td>
Gets the names of the snapshots created in the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_GetSnapshotNamesAsync">GetSnapshotNamesAsync</a></td><td>
Asynchronously gets the names of the snapshots created in the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_GetSnapshotsTreeview">GetSnapshotsTreeview</a></td><td>
Gets a tree-view of the snapshots created in the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_GetSnapshotsTreeviewAsync">GetSnapshotsTreeviewAsync</a></td><td>
Asynchronously gets a tree-view of the snapshots created in the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_InstallVmWareTools">InstallVmWareTools</a></td><td>
Installs VmWare Tools on the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_IsVmWareToolsInstalled">IsVmWareToolsInstalled</a></td><td>
Gets a value that determine whether VmWare Tools is installed in the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_IsVmWareToolsInstalledAsync">IsVmWareToolsInstalledAsync</a></td><td>
Asynchronously gets a value that determine whether VmWare Tools is installed in the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_ProcessKill">ProcessKill</a></td><td>
Kills a running process from the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_ProcessRun">ProcessRun</a></td><td>
Runs a new process in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_ProcessRunScript">ProcessRunScript</a></td><td>
Runs a script in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_ProcessRunScriptAsync">ProcessRunScriptAsync</a></td><td>
Asynchronously runs a script in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_SendKeystrokes">SendKeystrokes</a></td><td>
Send keystrokes to the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_SharedFolderAdd">SharedFolderAdd(VMWareVirtualMachine, VmSharedFolderInfo)</a></td><td>
Adds a new shared folder in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_SharedFolderAdd_1">SharedFolderAdd(VMWareVirtualMachine, String, String)</a></td><td>
Adds a new shared folder in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_SharedFolderRemove">SharedFolderRemove(VMWareVirtualMachine, VmSharedFolderInfo)</a></td><td>
Adds a new shared folder in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_SharedFolderRemove_1">SharedFolderRemove(VMWareVirtualMachine, String)</a></td><td>
Adds a new shared folder in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_SharedFoldersDisable">SharedFoldersDisable</a></td><td>
Enable shared folders features in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_SharedFoldersEnable">SharedFoldersEnable</a></td><td>
Enable shared folders features in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_SharedFolderSetAccess">SharedFolderSetAccess(VMWareVirtualMachine, VmSharedFolderInfo, Boolean)</a></td><td>
Sets the writable/readonly access of a shared folder in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_SharedFolderSetAccess_1">SharedFolderSetAccess(VMWareVirtualMachine, String, String, Boolean)</a></td><td>
Sets the writable/readonly access of a shared folder in the guest operating system of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_SnapshotCreate">SnapshotCreate</a></td><td>
Create a snapshot of the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_SnapshotDelete">SnapshotDelete</a></td><td>
Delete a snapshot from the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_SnapshotRestore">SnapshotRestore</a></td><td>
Revert the state of the specified virtual machine to the state of the specified snapshot.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_VmDelete">VmDelete</a></td><td>
Deletes the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_VmPause">VmPause</a></td><td>
Pause the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_VmReset">VmReset</a></td><td>
Reset the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_VmResume">VmResume</a></td><td>
Resume (unpause) the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_VmStart">VmStart</a></td><td>
Start the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_VmStop">VmStop</a></td><td>
Stop the specified virtual machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VmWare_VmRunWrapper_VmSuspend">VmSuspend</a></td><td>
Suspend the specified virtual machine.</td></tr></table>&nbsp;
<a href="#vmrunwrapper-class">Back to Top</a>

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
<a href="#vmrunwrapper-class">Back to Top</a>

## Examples
This is a code example that demonstrates how to get the running virtual machines, then run a program on each guest operating system. 
**VB**<br />
``` VB
Private vmRun As VmRunWrapper

Private Async Sub Test()

    Me.vmRun = New VmRunWrapper("C:\Program Files (x86)\VMWare\VMware VIX\vmrun.exe")

    Dim vmCount As Integer = Await Me.vmRun.GetRunningVmCountAsync()
    If (vmCount > 0) Then

        Dim vms As ReadOnlyCollection(Of VMWareVirtualMachine) = Await Me.vmRun.GetRunningVmsAsync()

        For Each vm As VMWareVirtualMachine In vms

            ' A valid guest username and password (if any) is required in order to use some of the functionalities of vmrun.exe program.
            vm.GuestOsCredential.Username = "guest username"
            vm.GuestOsCredential.Password = "guest password"

            ' Check whether VMWare-Tools are installed in the VM. 
            ' The VmWare-Tools are required by some of the functionalities of vmrun.exe program.
            Dim isVMWareToolsInstalled As Boolean = Await Me.vmRun.IsVmWareToolsInstalledAsync(vm)
            Console.WriteLine("VM Name: {0}; IsVMWareToolsInstalled: {1}'", vm.DisplayName, isVMWareToolsInstalled)

            If Not isVMWareToolsInstalled Then
                Me.vmRun.InstallVmWareTools(vm)
                Continue For
            End If

            Try
                ' Run a program on the guest operating system.
                Me.vmRun.ProcessRun(vm, "C:\program.exe", VmRunProgramFlags.NoWait Or VmRunProgramFlags.ActiveWindow Or VmRunProgramFlags.Interactive, "")

            Catch ex As VmRunException
                Throw

            Catch ex As Exception
                Throw

            End Try

        Next

    End If

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />