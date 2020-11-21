# RegistryValueType Enumeration
 

Specifies the data type of a registry value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum RegistryValueType
```

**VB**<br />
``` VB
Public Enumeration RegistryValueType
```

**VB Usage**<br />
``` VB Usage
Dim instance As RegistryValueType
```

**C++**<br />
``` C++
public enum class RegistryValueType
```

**F#**<br />
``` F#
type RegistryValueType
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.Shell.RegistryValueType.RegSZ">**RegSZ**</td><td>0</td><td>A null-terminated string. 

 This will be either a Unicode or an ANSI string.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.RegistryValueType.Binary">**Binary**</td><td>1</td><td>Binary data.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.RegistryValueType.Dword">**Dword**</td><td>2</td><td>Data represented as 32-bit integer (4 bytes). 

 DWORD equivalents are REG_DWORD_LITTLE_ENDIAN (least significant byte is at the lowest address) and REG_DWORD_BIG_ENDIAN (least significant byte is at the highest address).</td></tr><tr><td /><td target="F:DevCase.Core.Shell.RegistryValueType.Qword">**Qword**</td><td>3</td><td>Data represented as 64-bit integer (8 bytes). 

 QWORD equivalents are REG_QWORD_LITTLE_ENDIAN (least significant byte is at the lowest address) and REG_QWORD_BIG_ENDIAN (least significant byte is at the highest address).</td></tr><tr><td /><td target="F:DevCase.Core.Shell.RegistryValueType.ExpandSZ">**ExpandSZ**</td><td>4</td><td>A null-terminated string that contains unexpanded references to environment variables (for example, "%WinDir%").</td></tr><tr><td /><td target="F:DevCase.Core.Shell.RegistryValueType.MultiSZ">**MultiSZ**</td><td>5</td><td>A sequence of null-terminated strings, terminated by an empty string (\0). 

 The following is an example: 

`String1\0String2\0String3\0LastString\0\0`

 The first \0 terminates the first string, the second to the last \0 terminates the last string, and the final \0 terminates the sequence. 

 Note that the final terminator must be factored into the length of the string.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.RegistryValueType.RegNone">**RegNone**</td><td>6</td><td>No defined value type. 

 No data is stored in a key. 

 This data type is written to the registry by the system or an application. 

 In the registry editor, it is displayed as a binary value in a hexadecimal format.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.RegistryValueType.RegResourceList">**RegResourceList**</td><td>7</td><td>A series of nested arrays. 

 It stores a resource list used by a device driver or a hardware device controlled by that driver. 

 The system writes detected data to the '\ResourceMap' tree. 

 In the editor, this data is displayed as a binary value in a hexadecimal format.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.RegistryValueType.RegResourceRequirementsList">**RegResourceRequirementsList**</td><td>8</td><td>A series of nested arrays. 

 It is used to store a list of hardware drivers which can be used by a particular device driver or a hardware device controlled by that driver. 

 The system writes part of the list to the '\ResourceMap' tree. 

 Data is defined by the system. 

 In the editor, data is displayed as a binary value in a hexadecimal format.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.RegistryValueType.RegFullResourceDescriptor">**RegFullResourceDescriptor**</td><td>9</td><td>A series of nested arrays. 

 It stores a resource list that is used by a hardware device. 

 The system writes detected data to the '\HardwareDescription' tree. 

 In the editor, this data is displayed as a binary value in a hexadecimal format.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms724884%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms724884%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />