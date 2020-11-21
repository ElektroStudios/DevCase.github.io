# NativeMethods.DuplicateIcon Method 
 

Creates a duplicate of a specified icon.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", SetLastError = true)]
public static IntPtr DuplicateIcon(
	IntPtr hInst,
	IntPtr hicon
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", SetLastError := true>]
Public Shared Function DuplicateIcon ( 
	hInst As IntPtr,
	hicon As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hInst As IntPtr
Dim hicon As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.DuplicateIcon(hInst, 
	hicon)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", SetLastError = true)]
static IntPtr DuplicateIcon(
	IntPtr hInst, 
	IntPtr hicon
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", SetLastError = true)>]
static member DuplicateIcon : 
        hInst : IntPtr * 
        hicon : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hInst</dt><dd>Type: System.IntPtr<br />Reserved.</dd><dt>hicon</dt><dd>Type: System.IntPtr<br />Handle to the icon to be duplicated.</dd></dl>

#### Return Value
Type: IntPtr<br />If successful, the function returns the handle to the new icon that was created; otherwise, Zero.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb776411%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb776411%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />