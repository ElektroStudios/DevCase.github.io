# VMWareVirtualMachine.SharedFolders Property 
 

Gets the shared folders of this VM.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ReadOnlyCollection<VmSharedFolderInfo> SharedFolders { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property SharedFolders As ReadOnlyCollection(Of VmSharedFolderInfo)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As VMWareVirtualMachine
Dim value As ReadOnlyCollection(Of VmSharedFolderInfo)

value = instance.SharedFolders

```

**C++**<br />
``` C++
public:
property ReadOnlyCollection<VmSharedFolderInfo^>^ SharedFolders {
	ReadOnlyCollection<VmSharedFolderInfo^>^ get ();
}
```

**F#**<br />
``` F#
member SharedFolders : ReadOnlyCollection<VmSharedFolderInfo> with get

```


#### Property Value
Type: ReadOnlyCollection(<a href="T_DevCase_ThirdParty_VmWare_VmSharedFolderInfo">VmSharedFolderInfo</a>)<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.VmWare.VMWareVirtualMachine.SharedFolders"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">VMWareVirtualMachine Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />