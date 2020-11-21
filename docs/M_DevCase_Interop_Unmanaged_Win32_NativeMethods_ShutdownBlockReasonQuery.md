# NativeMethods.ShutdownBlockReasonQuery Method 
 

Retrieves the reason string set by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ShutdownBlockReasonCreate">ShutdownBlockReasonCreate(IntPtr, String)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static bool ShutdownBlockReasonQuery(
	IntPtr hWnd,
	StringBuilder buffer,
	ref uint refBufferSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ShutdownBlockReasonQuery ( 
	hWnd As IntPtr,
	buffer As StringBuilder,
	ByRef refBufferSize As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim buffer As StringBuilder
Dim refBufferSize As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.ShutdownBlockReasonQuery(hWnd, 
	buffer, refBufferSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static bool ShutdownBlockReasonQuery(
	IntPtr hWnd, 
	StringBuilder^ buffer, 
	unsigned int% refBufferSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member ShutdownBlockReasonQuery : 
        hWnd : IntPtr * 
        buffer : StringBuilder * 
        refBufferSize : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the main window of the application.</dd><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that receives the reason string. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the function retrieves the number of characters in the reason string.</dd><dt>refBufferSize</dt><dd>Type: System.UInt32<br />A pointer to a variable that specifies the size of the *buffer* parameter, in characters. 

 If the function succeeds, this variable receives the number of characters copied into the buffer, including the null-terminating character. 

 If the buffer is too small, the variable receives the required buffer size, in characters, not including the null-terminating character.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-shutdownblockreasonquery" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-shutdownblockreasonquery</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />