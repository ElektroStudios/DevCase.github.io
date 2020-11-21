# ShellExecuteInfo.InstApp Field
 

If SEE_MASK_NOCLOSEPROCESS is set and the ShellExecuteEx call succeeds, it sets this member to a value greater than 32. If the function fails, it is set to an SE_ERR_XXX error value that indicates the cause of the failure. Although hInstApp is declared as an HINSTANCE for compatibility with 16-bit Windows applications, it is not a true HINSTANCE. It can be cast only to an int and compared to either 32 or the following SE_ERR_XXX error codes.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr InstApp
```

**VB**<br />
``` VB
Public InstApp As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellExecuteInfo
Dim value As IntPtr

value = instance.InstApp

instance.InstApp = value
```

**C++**<br />
``` C++
public:
IntPtr InstApp
```

**F#**<br />
``` F#
val mutable InstApp: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellExecuteInfo">ShellExecuteInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />