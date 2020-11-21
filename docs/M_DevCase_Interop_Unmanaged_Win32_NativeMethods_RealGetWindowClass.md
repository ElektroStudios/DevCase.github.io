# NativeMethods.RealGetWindowClass Method 
 

Retrieves a string that specifies the window type.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint RealGetWindowClass(
	IntPtr hwnd,
	StringBuilder className,
	uint classNameMax
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function RealGetWindowClass ( 
	hwnd As IntPtr,
	className As StringBuilder,
	classNameMax As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hwnd As IntPtr
Dim className As StringBuilder
Dim classNameMax As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.RealGetWindowClass(hwnd, 
	className, classNameMax)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int RealGetWindowClass(
	IntPtr hwnd, 
	StringBuilder^ className, 
	unsigned int classNameMax
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member RealGetWindowClass : 
        hwnd : IntPtr * 
        className : StringBuilder * 
        classNameMax : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hwnd</dt><dd>Type: System.IntPtr<br />\[Missing <param name="hwnd"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.RealGetWindowClass(System.IntPtr,System.Text.StringBuilder,System.UInt32)"\]</dd><dt>className</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a string that receives the window type.</dd><dt>classNameMax</dt><dd>Type: System.UInt32<br />The length, in characters, of the buffer pointed to by the *className* parameter.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the number of characters copied to the specified. 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-realgetwindowclassw" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-realgetwindowclassw</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />