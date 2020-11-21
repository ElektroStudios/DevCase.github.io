# NativeMethods.GetKeyboardType Method 
 

Retrieves information about the current keyboard.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static int GetKeyboardType(
	int typeFlag
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetKeyboardType ( 
	typeFlag As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim typeFlag As Integer
Dim returnValue As Integer

returnValue = NativeMethods.GetKeyboardType(typeFlag)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static int GetKeyboardType(
	int typeFlag
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetKeyboardType : 
        typeFlag : int -> int 

```


#### Parameters
&nbsp;<dl><dt>typeFlag</dt><dd>Type: System.Int32<br />The type of keyboard information to be retrieved</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value specifies the requested information. 

 If the function fails and nTypeFlag is not one, the return value is zero; zero is a valid return value when nTypeFlag is one (keyboard subtype).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getkeyboardtype" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getkeyboardtype</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />