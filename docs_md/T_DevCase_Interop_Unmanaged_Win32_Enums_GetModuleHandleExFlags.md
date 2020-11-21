# GetModuleHandleExFlags Enumeration
 

Specifies the flags for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetModuleHandleEx">GetModuleHandleEx(GetModuleHandleExFlags, String, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum GetModuleHandleExFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration GetModuleHandleExFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As GetModuleHandleExFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class GetModuleHandleExFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type GetModuleHandleExFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetModuleHandleExFlags.Pin">**Pin**</td><td>1</td><td>The module stays loaded until the process is terminated, no matter how many times FreeLibrary is called 

 This flag cannot be combined with UnchangedReferenceCount flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetModuleHandleExFlags.UnchangedReferenceCount">**UnchangedReferenceCount**</td><td>2</td><td>The reference count for the module is not incremented. This flag is equivalent to the behavior of calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetModuleHandle">GetModuleHandle(String)</a>. 

 This flag cannot be combined with Pin flag. 

 Do not pass the retrieved module handle to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_FreeLibrary">FreeLibrary(SafeModuleHandle)</a> function; doing so can cause the DLL to be unmapped prematurely.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetModuleHandleExFlags.FromAddress">**FromAddress**</td><td>4</td><td>The moduleName parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetModuleHandleEx">GetModuleHandleEx(GetModuleHandleExFlags, String, IntPtr)</a> function is an address in the module.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms683200(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms683200(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />