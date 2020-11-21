# NativeMethods.SHObjectProperties Method 
 

Invokes the Properties context menu command on a Shell object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool SHObjectProperties(
	IntPtr hWndParent,
	SHObjectPropertiesFlags objectType,
	string objectName,
	string propertyPage
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function SHObjectProperties ( 
	hWndParent As IntPtr,
	objectType As SHObjectPropertiesFlags,
	objectName As String,
	propertyPage As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWndParent As IntPtr
Dim objectType As SHObjectPropertiesFlags
Dim objectName As String
Dim propertyPage As String
Dim returnValue As Boolean

returnValue = NativeMethods.SHObjectProperties(hWndParent, 
	objectType, objectName, propertyPage)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)]
static bool SHObjectProperties(
	IntPtr hWndParent, 
	SHObjectPropertiesFlags objectType, 
	String^ objectName, 
	String^ propertyPage
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)>]
static member SHObjectProperties : 
        hWndParent : IntPtr * 
        objectType : SHObjectPropertiesFlags * 
        objectName : string * 
        propertyPage : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWndParent</dt><dd>Type: System.IntPtr<br />The handle of the parent window of the dialog box. 

 This value can be NULL.</dd><dt>objectType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHObjectPropertiesFlags">DevCase.Interop.Unmanaged.Win32.Enums.SHObjectPropertiesFlags</a><br />A flag value that specifies the type of object.</dd><dt>objectName</dt><dd>Type: System.String<br />A null-terminated Unicode string that contains the object name. 

 The contents of the string are determined by the flag set in *objectType*.</dd><dt>propertyPage</dt><dd>Type: System.String<br />A null-terminated Unicode string that contains the name of the property sheet page to be opened initially. 

 Set this parameter to NULL to specify the default page.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if the command is successfully invoked; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shobjectproperties" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shobjectproperties</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />