# SymOptionFlags Enumeration
 

Flags combination for `symOptions` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SymSetOptions">SymSetOptions(SymOptionFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SymOptionFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SymOptionFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As SymOptionFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SymOptionFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SymOptionFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.None">**None**</td><td>0</td><td>Indicates that all options are turned off.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.AllowZeroAddress">**AllowZeroAddress**</td><td>16777216</td><td>Enables the use of symbols that do not have an address. 

 By default, `DbgHelp` filters out symbols that do not have an address.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.CaseInsensitive">**CaseInsensitive**</td><td>1</td><td>All symbol searches are insensitive to case.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.Debug">**Debug**</td><td>-2147483648</td><td>Pass debug output through `OutputDebugString` or the `SymRegisterCallbackProc64` callback function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.DeferredLoads">**DeferredLoads**</td><td>4</td><td>Symbols are not loaded until a reference is made requiring the symbols be loaded. 

 This is the fastest, most efficient way to use the symbol handler.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.ExactSymbols">**ExactSymbols**</td><td>1024</td><td>Do not load an unmatched `.pdb` file. 

 Do not load export symbols if all else fails.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.FailCriticalErrors">**FailCriticalErrors**</td><td>512</td><td>Do not display system dialog boxes when there is a media failure such as no media in a drive. 

 Instead, the failure happens silently.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.FavorCompressed">**FavorCompressed**</td><td>8388608</td><td>If there is both an uncompressed and a compressed file available, favor the compressed file. 

 This option is good for slow connections.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.IgnoreCvrec">**IgnoreCvrec**</td><td>128</td><td>Ignore path information in the CodeView record of the image header when loading a `.pdb` file.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.Include32BitModules">**Include32BitModules**</td><td>8192</td><td>When debugging on 64-bit Windows, include any 32-bit modules.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.LoadAnything">**LoadAnything**</td><td>64</td><td>Disable checks to ensure a file (`.exe`, `.dbg`, or `.pdb`) is the correct file. 

 Instead, load the first file located.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.LoadLines">**LoadLines**</td><td>16</td><td>Loads line number information.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.NOCpp">**NOCpp**</td><td>8</td><td>All `C++` decorated symbols containing the symbol separator "`::`" are replaced by "`__`". 

 This option exists for debuggers that cannot handle parsing real `C++` symbol names.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.NOPrompts">**NOPrompts**</td><td>524288</td><td>Prevents prompting for validation from the symbol server.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.NOUnqualifiedLoads">**NOUnqualifiedLoads**</td><td>256</td><td>Prevents symbols from being loaded when the caller examines symbols across multiple modules. 

 Examine only the module whose symbols have already been loaded.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.Secure">**Secure**</td><td>262144</td><td>`DbgHelp` will not load any symbol server other than `SymSrv`. 

`SymSrv` will not use the downstream store specified in `_NT_SYMBOL_PATH`. 

 After this flag has been set, it cannot be cleared.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags.UndName">**UndName**</td><td>2</td><td>All symbols are presented in undecorated form. 

 This option has no effect on global or local symbols because they are stored undecorated. 

 This option applies only to public symbols.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms681366%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms681366%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />