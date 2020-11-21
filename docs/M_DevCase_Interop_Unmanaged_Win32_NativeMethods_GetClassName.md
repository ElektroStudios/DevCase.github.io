# NativeMethods.GetClassName Method (IntPtr, StringBuilder, Int32)
 

Retrieves the name of the class to which the specified window belongs.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static int GetClassName(
	IntPtr hWnd,
	StringBuilder className,
	int maxCount
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetClassName ( 
	hWnd As IntPtr,
	className As StringBuilder,
	maxCount As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim className As StringBuilder
Dim maxCount As Integer
Dim returnValue As Integer

returnValue = NativeMethods.GetClassName(hWnd, 
	className, maxCount)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static int GetClassName(
	IntPtr hWnd, 
	StringBuilder^ className, 
	int maxCount
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetClassName : 
        hWnd : IntPtr * 
        className : StringBuilder * 
        maxCount : int -> int 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window and, indirectly, the class to which the window belongs.</dd><dt>className</dt><dd>Type: System.Text.StringBuilder<br />The class name string.</dd><dt>maxCount</dt><dd>Type: System.Int32<br />The length of the *className* buffer, in characters. 

 The buffer must be large enough to include the terminating null character; otherwise, the class name string is truncated to *maxCount*-1 characters.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value is the number of characters copied to the buffer, not including the terminating null character. 

 If the function fails, the return value is `0`. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633582(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633582(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetClassName">GetClassName Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />