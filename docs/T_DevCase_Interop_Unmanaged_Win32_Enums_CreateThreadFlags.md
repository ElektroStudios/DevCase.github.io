# CreateThreadFlags Enumeration
 

Specifies the flags that control the creation of a thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum CreateThreadFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration CreateThreadFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As CreateThreadFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class CreateThreadFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type CreateThreadFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateThreadFlags.Default">**Default**</td><td>0</td><td>The thread runs immediately after creation.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateThreadFlags.CreateSuspended">**CreateSuspended**</td><td>4</td><td>The thread is created in a suspended state, and does not run until the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ResumeThread">ResumeThread(SafeAccessTokenHandle)</a> function is called.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateThreadFlags.StackSizeParamIsAReservation">**StackSizeParamIsAReservation**</td><td>65536</td><td>The dwStackSize parameter specifies the initial reserve size of the stack. 

 If this flag is not specified, `stackSize` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateThread">CreateThread(SecurityAttributes, IntPtr, IntPtr, IntPtr, CreateThreadFlags, UInt32)</a> specifies the commit size.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms682453(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms682453(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />