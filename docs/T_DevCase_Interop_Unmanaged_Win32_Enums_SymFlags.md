# SymFlags Enumeration
 

Flags combination for <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_Flags">Flags</a> property.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SymFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SymFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As SymFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SymFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SymFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.ValuePresent">**ValuePresent**</td><td>1</td><td>The Value member is used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.Register">**Register**</td><td>8</td><td>The symbol is a register. The Register member is used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.RegisterRelative">**RegisterRelative**</td><td>16</td><td>Offsets are register relative.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.FrameRelative">**FrameRelative**</td><td>32</td><td>Offsets are frame relative.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.Parameter">**Parameter**</td><td>64</td><td>The symbol is a parameter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.Local">**Local**</td><td>128</td><td>The symbol is a local variable.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.Constant">**Constant**</td><td>256</td><td>The symbol is a constant.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.Export">**Export**</td><td>512</td><td>The symbol is from the export table.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.Forwarder">**Forwarder**</td><td>1024</td><td>The symbol is a forwarder.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.Function">**Function**</td><td>2048</td><td>The symbol is a known function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.Virtual">**Virtual**</td><td>4096</td><td>The symbol is a virtual symbol created by the `SymAddSymbol` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.Thunk">**Thunk**</td><td>8192</td><td>The symbol is a thunk.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.TlsRelative">**TlsRelative**</td><td>16384</td><td>The symbol is an offset into the TLS data area.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.Slot">**Slot**</td><td>32768</td><td>The symbol is a managed code slot.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.IlRelative">**IlRelative**</td><td>65536</td><td>The symbol address is an offset relative to the beginning of the intermediate language block. 

 This applies to managed code only.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.Metadata">**Metadata**</td><td>131072</td><td>The symbol is managed metadata.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymFlags.ClrToken">**ClrToken**</td><td>262144</td><td>The symbol is a CLR token.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms680686%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms680686%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />