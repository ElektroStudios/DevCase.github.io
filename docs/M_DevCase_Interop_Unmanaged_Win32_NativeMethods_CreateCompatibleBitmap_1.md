# NativeMethods.CreateCompatibleBitmap Method (SafeHandle, Int32, Int32)
 

Creates a bitmap compatible with the device that is associated with the specified device context.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll")]
public static IntPtr CreateCompatibleBitmap(
	SafeHandle hdc,
	int width,
	int height
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll">]
Public Shared Function CreateCompatibleBitmap ( 
	hdc As SafeHandle,
	width As Integer,
	height As Integer
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hdc As SafeHandle
Dim width As Integer
Dim height As Integer
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateCompatibleBitmap(hdc, 
	width, height)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll")]
static IntPtr CreateCompatibleBitmap(
	SafeHandle^ hdc, 
	int width, 
	int height
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll")>]
static member CreateCompatibleBitmap : 
        hdc : SafeHandle * 
        width : int * 
        height : int -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the Device Context (DC).</dd><dt>width</dt><dd>Type: System.Int32<br />The bitmap width, in pixels.</dd><dt>height</dt><dd>Type: System.Int32<br />The bitmap height, in pixels.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the compatible bitmap (DDB). 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183488(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183488(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateCompatibleBitmap">CreateCompatibleBitmap Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />