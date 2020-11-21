# NativeMethods.FindWindow Method 
 

Retrieves a handle to the top-level window whose class name and window name match the specified strings. 

 This function does not search child windows. This function does not perform a case-sensitive search. 

 To search child windows, beginning with a specified child window, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_FindWindowEx">FindWindowEx(IntPtr, IntPtr, String, String)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr FindWindow(
	string className,
	string windowName
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function FindWindow ( 
	className As String,
	windowName As String
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim className As String
Dim windowName As String
Dim returnValue As IntPtr

returnValue = NativeMethods.FindWindow(className, 
	windowName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr FindWindow(
	String^ className, 
	String^ windowName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member FindWindow : 
        className : string * 
        windowName : string -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>className</dt><dd>Type: System.String<br />The class name or a class atom created by a previous call to the RegisterClass or RegisterClassEx function. 

 The atom must be in the low-order word of *className*; the high-order word must be zero. 

 If *className* is NULL, it finds any window whose title matches the *windowName* parameter.</dd><dt>windowName</dt><dd>Type: System.String<br />The window name (the window's titlebar title). 

 If this parameter is a null reference (`Nothing` in Visual Basic), all window names match.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the window that has the specified class name and window name. 

 If the function fails, the return value is a null reference (`Nothing` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633499%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633499%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />