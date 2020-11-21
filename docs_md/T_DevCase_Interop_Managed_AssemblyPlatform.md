# AssemblyPlatform Enumeration
 

Specifies a platform version of common language runtime (CLR).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum AssemblyPlatform
```

**VB**<br />
``` VB
Public Enumeration AssemblyPlatform
```

**VB Usage**<br />
``` VB Usage
Dim instance As AssemblyPlatform
```

**C++**<br />
``` C++
public enum class AssemblyPlatform
```

**F#**<br />
``` F#
type AssemblyPlatform
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Managed.AssemblyPlatform.AnyCpu">**AnyCpu**</td><td>0</td><td>An assembly to run on any platform. 

 The application will run as a 32-bit application on 32-bit versions of Windows and as a 64-bit application on 64-bit versions of Windows. 

 This flag is the default value.</td></tr><tr><td /><td target="F:DevCase.Interop.Managed.AssemblyPlatform.AnyCpu32bitPreferred">**AnyCpu32bitPreferred**</td><td>1</td><td>An assembly to run on any platform. 

 The assembly will run as a 32-bit application on both 32-bit and 64-bit versions of Windows. 

 This flag is valid only for executables (.EXE) and requires .NET Framework 4.5.</td></tr><tr><td /><td target="F:DevCase.Interop.Managed.AssemblyPlatform.X86">**X86**</td><td>2</td><td>An assembly to be run by the 32-bit, x86-compatible CLR.</td></tr><tr><td /><td target="F:DevCase.Interop.Managed.AssemblyPlatform.X64">**X64**</td><td>3</td><td>An assembly to be run by the 64-bit CLR on a computer that supports the AMD64 or EM64T instruction set.</td></tr><tr><td /><td target="F:DevCase.Interop.Managed.AssemblyPlatform.Itanium">**Itanium**</td><td>4</td><td>An assembly to be run by the 64-bit CLR on a computer with an Itanium processor.</td></tr><tr><td /><td target="F:DevCase.Interop.Managed.AssemblyPlatform.Arm">**Arm**</td><td>5</td><td>An assembly to be run on a computer with an ARM (Advanced RISC Machine) processor.</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />