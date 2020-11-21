# NativeMethods.LoadIcon Method 
 

Loads the specified icon resource from the executable (.exe) file associated with an application instance.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr LoadIcon(
	IntPtr hInstance,
	string name
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function LoadIcon ( 
	hInstance As IntPtr,
	name As String
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hInstance As IntPtr
Dim name As String
Dim returnValue As IntPtr

returnValue = NativeMethods.LoadIcon(hInstance, 
	name)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr LoadIcon(
	IntPtr hInstance, 
	[InAttribute] String^ name
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member LoadIcon : 
        hInstance : IntPtr * 
        name : string -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hInstance</dt><dd>Type: System.IntPtr<br />A handle to an instance of the module whose executable file contains the icon to be loaded. 

 This parameter must be Zero when a standard icon is being loaded.</dd><dt>name</dt><dd>Type: System.String<br />The name of the icon resource to be loaded. 

 Alternatively, this parameter can contain the resource identifier in the low-order word and zero in the high-order word.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the newly loaded icon. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648072(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648072(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />