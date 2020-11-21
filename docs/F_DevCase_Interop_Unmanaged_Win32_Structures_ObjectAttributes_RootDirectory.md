# ObjectAttributes.RootDirectory Field
 

Optional handle to the root object directory for the path name specified by the ObjectName member. 

 If RootDirectory is Zero, <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_ObjectName">ObjectName</a> must point to a fully qualified object name that includes the full path to the target object. 

 If RootDirectory is not Zero, <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_ObjectName">ObjectName</a> specifies an object name relative to the RootDirectory directory. 

 The RootDirectory handle can refer to a file system directory or an object directory in the object manager namespace.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr RootDirectory
```

**VB**<br />
``` VB
Public RootDirectory As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As ObjectAttributes
Dim value As IntPtr

value = instance.RootDirectory

instance.RootDirectory = value
```

**C++**<br />
``` C++
public:
IntPtr RootDirectory
```

**F#**<br />
``` F#
val mutable RootDirectory: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes">ObjectAttributes Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />