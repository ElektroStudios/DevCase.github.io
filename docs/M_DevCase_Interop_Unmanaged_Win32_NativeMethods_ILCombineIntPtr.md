# NativeMethods.ILCombineIntPtr Method 
 

Combines two `ITEMIDLIST` structures.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", EntryPoint = "ILCombine", SetLastError = true)]
public static IntPtr ILCombineIntPtr(
	IntPtr pidlParent,
	IntPtr pidlChild
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", EntryPoint := "ILCombine", SetLastError := true>]
Public Shared Function ILCombineIntPtr ( 
	pidlParent As IntPtr,
	pidlChild As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim pidlParent As IntPtr
Dim pidlChild As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.ILCombineIntPtr(pidlParent, 
	pidlChild)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", EntryPoint = L"ILCombine", SetLastError = true)]
static IntPtr ILCombineIntPtr(
	IntPtr pidlParent, 
	IntPtr pidlChild
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", EntryPoint = "ILCombine", SetLastError = true)>]
static member ILCombineIntPtr : 
        pidlParent : IntPtr * 
        pidlChild : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>pidlParent</dt><dd>Type: System.IntPtr<br />A pointer to the first `ITEMIDLIST` structure.</dd><dt>pidlChild</dt><dd>Type: System.IntPtr<br />A pointer to the second `ITEMIDLIST` structure. 

 This structure is appended to the structure pointed to by *pidlParent*.</dd></dl>

#### Return Value
Type: IntPtr<br />Returns an `ITEMIDLIST` containing the combined structures. 

 If you set either *pidlParent* or *pidlChild* to Zero, the returned `ITEMIDLIST` structure is a clone of the non-NULL parameter. 

 Returns NULL if *pidlParent* and *pidlChild* are both set to Zero.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb776437(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb776437(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />