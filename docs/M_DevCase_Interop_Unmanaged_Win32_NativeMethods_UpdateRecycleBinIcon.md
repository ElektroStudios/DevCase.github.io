# NativeMethods.UpdateRecycleBinIcon Method 
 

Updates the Recycle Bin icon on the desktop to reflect the state of the systemwide Recycle Bin, for example if an error occurs during an <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EmptyRecycleBin">EmptyRecycleBin(IntPtr, String, SHEmptyRecycleBinFlags)</a> call. 

 But since the other Recycle Bin management functions will update this icon on their own, there's almost no reason why your applications would need to call this function explicitly.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", EntryPoint = "SHUpdateRecycleBinIcon")]
public static bool UpdateRecycleBinIcon()
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", EntryPoint := "SHUpdateRecycleBinIcon">]
Public Shared Function UpdateRecycleBinIcon As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = NativeMethods.UpdateRecycleBinIcon()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", EntryPoint = L"SHUpdateRecycleBinIcon")]
static bool UpdateRecycleBinIcon()
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", EntryPoint = "SHUpdateRecycleBinIcon")>]
static member UpdateRecycleBinIcon : unit -> bool 

```


#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if operation succeeds, `false` (`False` in Visual Basic) otherwise.

## Remarks


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />