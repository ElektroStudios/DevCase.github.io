# NativeMethods.GetMenuPosFromID Method 
 

Determines the position of an item in a menu. Used in the case where the item's ID is known.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", ExactSpelling = true, SetLastError = true)]
public static int GetMenuPosFromID(
	IntPtr hMenu,
	uint id
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetMenuPosFromID ( 
	hMenu As IntPtr,
	id As UInteger
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hMenu As IntPtr
Dim id As UInteger
Dim returnValue As Integer

returnValue = NativeMethods.GetMenuPosFromID(hMenu, 
	id)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", ExactSpelling = true, SetLastError = true)]
static int GetMenuPosFromID(
	IntPtr hMenu, 
	unsigned int id
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", ExactSpelling = true, SetLastError = true)>]
static member GetMenuPosFromID : 
        hMenu : IntPtr * 
        id : uint32 -> int 

```


#### Parameters
&nbsp;<dl><dt>hMenu</dt><dd>Type: System.IntPtr<br />The handle of the menu.</dd><dt>id</dt><dd>Type: System.UInt32<br />An application-defined 16-bit value that identifies the menu item.</dd></dl>

#### Return Value
Type: Int32<br />The item's zero-based position in the menu.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-getmenuposfromid" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-getmenuposfromid</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />