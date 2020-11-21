# SHObjectPropertiesFlags Enumeration
 

Flags for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHObjectProperties">SHObjectProperties(IntPtr, SHObjectPropertiesFlags, String, String)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SHObjectPropertiesFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SHObjectPropertiesFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As SHObjectPropertiesFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SHObjectPropertiesFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SHObjectPropertiesFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHObjectPropertiesFlags.PrinterName">**PrinterName**</td><td>1</td><td>Contains the friendly name of a printer.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHObjectPropertiesFlags.FilePath">**FilePath**</td><td>2</td><td>Contains a fully qualified file name.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHObjectPropertiesFlags.VolumeGuid">**VolumeGuid**</td><td>4</td><td>Contains either (a) a volume name of the form \?\Volume{GUID}, where {GUID} is a globally unique identifier (for example, "\?\Volume{2eca078d-5cbc-43d3-aff8-7e8511f60d0e})", or (b) a drive path (for example, "C:").</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shobjectproperties" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shobjectproperties</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />