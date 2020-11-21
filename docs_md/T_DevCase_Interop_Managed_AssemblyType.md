# AssemblyType Enumeration
 

Specifies a CompilerParameters target assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum AssemblyType
```

**VB**<br />
``` VB
Public Enumeration AssemblyType
```

**VB Usage**<br />
``` VB Usage
Dim instance As AssemblyType
```

**C++**<br />
``` C++
public enum class AssemblyType
```

**F#**<br />
``` F#
type AssemblyType
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Managed.AssemblyType.Console">**Console**</td><td>0</td><td>An executable console application or Command line interface (CLI). 

 The output file is created with an extension of .exe.</td></tr><tr><td /><td target="F:DevCase.Interop.Managed.AssemblyType.WinExe">**WinExe**</td><td>1</td><td>An executable Windows-based application or Graphical user interface (GUI). 

 The output file is created with an extension of .exe.</td></tr><tr><td /><td target="F:DevCase.Interop.Managed.AssemblyType.WinExeContainer">**WinExeContainer**</td><td>2</td><td>An executable Windows-based application that must be run in an app container. 

 This setting is designed to be used for Windows 8.x Store applications. 

 The output file is created with an extension of .exe.</td></tr><tr><td /><td target="F:DevCase.Interop.Managed.AssemblyType.WinMdObj">**WinMdObj**</td><td>3</td><td>An intermediate file that you can convert to a Windows Runtime binary (.winmd) file. 

 The .winmd file can be consumed by JavaScript and C++ programs, in addition to managed language programs. 

 The output file name takes the name of the input file.</td></tr><tr><td /><td target="F:DevCase.Interop.Managed.AssemblyType.DynamicLinkLibrary">**DynamicLinkLibrary**</td><td>4</td><td>A Dynamic-link library. 

 The output file is created with an extension of .dll.</td></tr><tr><td /><td target="F:DevCase.Interop.Managed.AssemblyType.Module">**Module**</td><td>5</td><td>A module that can be added to an assembly. 

 The output file is created with an extension of .netmodule.</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />