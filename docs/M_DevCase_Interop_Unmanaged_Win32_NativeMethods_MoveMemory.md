# NativeMethods.MoveMemory Method (IntPtr, IntPtr, IntPtr)
 

Moves a block of memory from one location to another.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", EntryPoint = "RtlMoveMemory", CallingConvention = CallingConvention.StdCall, 
	CharSet = CharSet.Auto, ExactSpelling = true, SetLastError = true)]
public static void MoveMemory(
	IntPtr destination,
	IntPtr source,
	IntPtr length
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", EntryPoint := "RtlMoveMemory", CallingConvention := CallingConvention.StdCall, 
	CharSet := CharSet.Auto, ExactSpelling := true, SetLastError := true>]
Public Shared Sub MoveMemory ( 
	destination As IntPtr,
	source As IntPtr,
	length As IntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim destination As IntPtr
Dim source As IntPtr
Dim length As IntPtrNativeMethods.MoveMemory(destination, source, 
	length)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", EntryPoint = L"RtlMoveMemory", CallingConvention = CallingConvention::StdCall, 
	CharSet = CharSet::Auto, ExactSpelling = true, SetLastError = true)]
static void MoveMemory(
	IntPtr destination, 
	IntPtr source, 
	IntPtr length
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", EntryPoint = "RtlMoveMemory", CallingConvention = CallingConvention.StdCall, 
	CharSet = CharSet.Auto, ExactSpelling = true, SetLastError = true)>]
static member MoveMemory : 
        destination : IntPtr * 
        source : IntPtr * 
        length : IntPtr -> unit 

```


#### Parameters
&nbsp;<dl><dt>destination</dt><dd>Type: System.IntPtr<br />A pointer to the starting address of the move destination.</dd><dt>source</dt><dd>Type: System.IntPtr<br />A pointer to the starting address of the block of memory to be moved.</dd><dt>length</dt><dd>Type: System.IntPtr<br />The size of the block of memory to move, in bytes.</dd></dl>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa366788(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa366788(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_MoveMemory">MoveMemory Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />