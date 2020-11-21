# AppPolicyProcessTerminationMethod Enumeration
 

Indicates the method used to end a process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum AppPolicyProcessTerminationMethod
```

**VB**<br />
``` VB
Public Enumeration AppPolicyProcessTerminationMethod
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppPolicyProcessTerminationMethod
```

**C++**<br />
``` C++
public enum class AppPolicyProcessTerminationMethod
```

**F#**<br />
``` F#
type AppPolicyProcessTerminationMethod
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AppPolicyProcessTerminationMethod.ExitProcess">**ExitProcess**</td><td>0</td><td>Allows DLLs to execute code at shutdown. 

 This value is expected for a desktop application, or for a Desktop Bridge application.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AppPolicyProcessTerminationMethod.TerminateProcess">**TerminateProcess**</td><td>1</td><td>Immediately ends the process. 

 This value is expected for a UWP (Universal Windows Platform) app.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/appmodel/ne-appmodel-apppolicyprocessterminationmethod" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/appmodel/ne-appmodel-apppolicyprocessterminationmethod</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />