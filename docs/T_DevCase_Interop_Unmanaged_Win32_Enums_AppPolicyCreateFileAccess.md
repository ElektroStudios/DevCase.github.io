# AppPolicyCreateFileAccess Enumeration
 

Indicates whether a process has full or restricted access to the I/O devices (file, file stream, directory, physical disk, volume, console buffer, tape drive, communications resource, mailslot, and pipe).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum AppPolicyCreateFileAccess
```

**VB**<br />
``` VB
Public Enumeration AppPolicyCreateFileAccess
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppPolicyCreateFileAccess
```

**C++**<br />
``` C++
public enum class AppPolicyCreateFileAccess
```

**F#**<br />
``` F#
type AppPolicyCreateFileAccess
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AppPolicyCreateFileAccess.Full">**Full**</td><td>0</td><td>Indicates that the process has full access to the IO devices. 

 This value is expected for a desktop application, or for a Desktop Bridge application.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AppPolicyCreateFileAccess.Limited">**Limited**</td><td>1</td><td>Indicates that the process has limited access to the IO devices. 

 This value is expected for a UWP app.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/appmodel/ne-appmodel-apppolicycreatefileaccess" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/appmodel/ne-appmodel-apppolicycreatefileaccess</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />