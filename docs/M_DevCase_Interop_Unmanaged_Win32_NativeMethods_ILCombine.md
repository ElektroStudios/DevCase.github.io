# NativeMethods.ILCombine Method 
 

Combines two `ITEMIDLIST` structures.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", SetLastError = true)]
public static PIDL ILCombine(
	IntPtr pidlParent,
	IntPtr pidlChild
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", SetLastError := true>]
Public Shared Function ILCombine ( 
	pidlParent As IntPtr,
	pidlChild As IntPtr
) As PIDL
```

**VB Usage**<br />
``` VB Usage
Dim pidlParent As IntPtr
Dim pidlChild As IntPtr
Dim returnValue As PIDL

returnValue = NativeMethods.ILCombine(pidlParent, 
	pidlChild)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", SetLastError = true)]
static PIDL^ ILCombine(
	IntPtr pidlParent, 
	IntPtr pidlChild
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", SetLastError = true)>]
static member ILCombine : 
        pidlParent : IntPtr * 
        pidlChild : IntPtr -> PIDL 

```


#### Parameters
&nbsp;<dl><dt>pidlParent</dt><dd>Type: System.IntPtr<br />A pointer to the first `ITEMIDLIST` structure.</dd><dt>pidlChild</dt><dd>Type: System.IntPtr<br />A pointer to the second `ITEMIDLIST` structure. 

 This structure is appended to the structure pointed to by *pidlParent*.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a><br />Returns an `ITEMIDLIST` containing the combined structures. 

 If you set either *pidlParent* or *pidlChild* to Zero, the returned `ITEMIDLIST` structure is a clone of the non-NULL parameter. 

 Returns NULL if *pidlParent* and *pidlChild* are both set to Zero.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb776437(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb776437(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />