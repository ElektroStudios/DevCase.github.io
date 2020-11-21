# VMWareVirtualMachine.GuestOsCredential Property 
 

Gets or sets the username and password of the running user-account in the guest operating system of this VM. 

 The credential is required to perform some I/O operations with VMWare's vmrun.exe program. So you must set this credential before using vmrun.exe.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public GuestOsCredential GuestOsCredential { get; set; }
```

**VB**<br />
``` VB
Public Property GuestOsCredential As GuestOsCredential
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As VMWareVirtualMachine
Dim value As GuestOsCredential

value = instance.GuestOsCredential

instance.GuestOsCredential = value
```

**C++**<br />
``` C++
public:
property GuestOsCredential^ GuestOsCredential {
	GuestOsCredential^ get ();
	void set (GuestOsCredential^ value);
}
```

**F#**<br />
``` F#
member GuestOsCredential : GuestOsCredential with get, set

```


#### Property Value
Type: <a href="T_DevCase_ThirdParty_VmWare_GuestOsCredential">GuestOsCredential</a><br />\[Missing <value> documentation for "P:DevCase.ThirdParty.VmWare.VMWareVirtualMachine.GuestOsCredential"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">VMWareVirtualMachine Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />