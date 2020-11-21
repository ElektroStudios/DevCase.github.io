# NativeMethods.CreateDC Method 
 

Creates a device context (DC) for a device using the specified name.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr CreateDC(
	string lpszDriver,
	string lpszDevice,
	string lpszOutput,
	IntPtr lpInitData
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", CharSet := CharSet.Ansi, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function CreateDC ( 
	lpszDriver As String,
	lpszDevice As String,
	lpszOutput As String,
	lpInitData As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim lpszDriver As String
Dim lpszDevice As String
Dim lpszOutput As String
Dim lpInitData As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateDC(lpszDriver, 
	lpszDevice, lpszOutput, lpInitData)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", CharSet = CharSet::Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr CreateDC(
	String^ lpszDriver, 
	String^ lpszDevice, 
	String^ lpszOutput, 
	IntPtr lpInitData
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member CreateDC : 
        lpszDriver : string * 
        lpszDevice : string * 
        lpszOutput : string * 
        lpInitData : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>lpszDriver</dt><dd>Type: System.String<br />A pointer to a null-terminated character string that specifies either "`DISPLAY`" or the name of a specific display device. 

 For printing, we recommend that you pass a null reference (`Nothing` in Visual Basic) to *lpszDriver* because `GDI` ignores *lpszDriver* for printer devices.</dd><dt>lpszDevice</dt><dd>Type: System.String<br />A pointer to a null-terminated character string that specifies the name of the specific output device being used, as shown by the Print Manager (for example, "`Epson FX-80`"). It is not the printer model name. The *lpszDevice* parameter must be used. 

 To obtain valid names for displays, call `EnumDisplayDevices` function. 

 If *lpszDriver* is "`DISPLAY`" or the device name of a specific display device, then *lpszDevice* must be a null reference (`Nothing` in Visual Basic) or that same device name. 

 If *lpszDevice* is a null reference (`Nothing` in Visual Basic), then a device context (DC) is created for the primary display device. 

 If there are multiple monitors on the system, calling `CreateDC("DISPLAY", Nothing, Nothing, Nothing)` will create a device context (DC) covering all the monitors.</dd><dt>lpszOutput</dt><dd>Type: System.String<br />This parameter is ignored and should be set to a null reference (`Nothing` in Visual Basic). It is provided only for compatibility with 16-bit Windows.</dd><dt>lpInitData</dt><dd>Type: System.IntPtr<br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode</a> structure containing device-specific initialization data for the device driver. 

 The `DocumentProperties` function retrieves this structure filled in for a specified device. 

 The *lpInitData* parameter must be a null reference (`Nothing` in Visual Basic) if the device driver is to use the default initialization (if any) specified by the user.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the handle to a DC for the specified device. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183490%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183490%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />