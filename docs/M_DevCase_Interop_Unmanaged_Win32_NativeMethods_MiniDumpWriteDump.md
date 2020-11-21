# NativeMethods.MiniDumpWriteDump Method (IntPtr, Int32, SafeHandle, MiniDumpType, MiniDumpExceptionInformation, IntPtr, IntPtr)
 

Writes user-mode minidump information to the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DbgHelp.dll", CallingConvention = CallingConvention.StdCall, 
	CharSet = CharSet.Unicode, ExactSpelling = true, SetLastError = true)]
public static bool MiniDumpWriteDump(
	IntPtr hProcess,
	int processId,
	SafeHandle hFile,
	MiniDumpType dumpType,
	ref MiniDumpExceptionInformation refExpParam,
	IntPtr userStreamParam,
	IntPtr callbackParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("DbgHelp.dll", CallingConvention := CallingConvention.StdCall, 
	CharSet := CharSet.Unicode, ExactSpelling := true, SetLastError := true>]
Public Shared Function MiniDumpWriteDump ( 
	hProcess As IntPtr,
	processId As Integer,
	hFile As SafeHandle,
	dumpType As MiniDumpType,
	ByRef refExpParam As MiniDumpExceptionInformation,
	userStreamParam As IntPtr,
	callbackParam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim processId As Integer
Dim hFile As SafeHandle
Dim dumpType As MiniDumpType
Dim refExpParam As MiniDumpExceptionInformation
Dim userStreamParam As IntPtr
Dim callbackParam As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.MiniDumpWriteDump(hProcess, 
	processId, hFile, dumpType, refExpParam, 
	userStreamParam, callbackParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DbgHelp.dll", CallingConvention = CallingConvention::StdCall, 
	CharSet = CharSet::Unicode, ExactSpelling = true, SetLastError = true)]
static bool MiniDumpWriteDump(
	IntPtr hProcess, 
	int processId, 
	SafeHandle^ hFile, 
	MiniDumpType dumpType, 
	MiniDumpExceptionInformation% refExpParam, 
	IntPtr userStreamParam, 
	IntPtr callbackParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DbgHelp.dll", CallingConvention = CallingConvention.StdCall, 
	CharSet = CharSet.Unicode, ExactSpelling = true, SetLastError = true)>]
static member MiniDumpWriteDump : 
        hProcess : IntPtr * 
        processId : int * 
        hFile : SafeHandle * 
        dumpType : MiniDumpType * 
        refExpParam : MiniDumpExceptionInformation byref * 
        userStreamParam : IntPtr * 
        callbackParam : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process for which the information is to be generated. 

 This handle must have <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryRead</a> access to the process. 

 If handle information is to be collected then <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">DuplicateHandle</a> access is also required.</dd><dt>processId</dt><dd>Type: System.Int32<br />The identifier of the process for which the information is to be generated.</dd><dt>hFile</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the file in which the information is to be written.</dd><dt>dumpType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MiniDumpType">DevCase.Interop.Unmanaged.Win32.Enums.MiniDumpType</a><br />The type of information to be generated.</dd><dt>refExpParam</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MiniDumpExceptionInformation">DevCase.Interop.Unmanaged.Win32.Structures.MiniDumpExceptionInformation</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MiniDumpExceptionInformation">MiniDumpExceptionInformation</a> structure describing the client exception that caused the minidump to be generated. 

 If the value of this parameter is a null reference (`Nothing` in Visual Basic), no exception information is included in the minidump file.</dd><dt>userStreamParam</dt><dd>Type: System.IntPtr<br />A pointer to a `MINIDUMP_USER_STREAM_INFORMATION` structure. 

 If the value of this parameter is Zero, no user-defined information is included in the minidump file.</dd><dt>callbackParam</dt><dd>Type: System.IntPtr<br />A pointer to a `MINIDUMP_CALLBACK_INFORMATION` structure that specifies a callback routine which is to receive extended minidump information. 

 If the value of this parameter is Zero, no callbacks are performed.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic); otherwise, the return value is `false` (`False` in Visual Basic). 

 To retrieve extended error information, call GetLastWin32Error(). Note that the last error will be an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/ms680360%28VS.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/ms680360%28VS.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_MiniDumpWriteDump">MiniDumpWriteDump Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />