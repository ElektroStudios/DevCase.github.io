# SymLoadModuleFlags Enumeration
 

Flags combination for `flags` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SymLoadModuleEx">SymLoadModuleEx(IntPtr, IntPtr, String, String, UInt64, Int32, IntPtr, SymLoadModuleFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SymLoadModuleFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SymLoadModuleFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As SymLoadModuleFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SymLoadModuleFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SymLoadModuleFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymLoadModuleFlags.ModuleAndSymbols">**ModuleAndSymbols**</td><td>0</td><td>Loads the module and the symbols for the module.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymLoadModuleFlags.OnlyModule">**OnlyModule**</td><td>4</td><td>Loads the module but not the symbols for the module.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymLoadModuleFlags.Virtual">**Virtual**</td><td>1</td><td>Creates a virtual module named `ModuleName` at the address specified in `baseOfDll` parameter. 

 To add symbols to this module, call the `SymAddSymbol` function.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms681353%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms681353%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />