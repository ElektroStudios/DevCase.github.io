# IShellFolder.ParseDisplayName Method 
 

Translates the display name of a file object or a folder into an item identifier list.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void ParseDisplayName(
	IntPtr hwnd,
	[OptionalAttribute] IBindCtx bindContext,
	string displayName,
	ref uint refEaten,
	ref PIDL refPidl,
	out ShellItemAttributesMask refAttributes
)
```

**VB**<br />
``` VB
Sub ParseDisplayName ( 
	hwnd As IntPtr,
	<OptionalAttribute> bindContext As IBindCtx,
	displayName As String,
	ByRef refEaten As UInteger,
	ByRef refPidl As PIDL,
	<OutAttribute> ByRef refAttributes As ShellItemAttributesMask
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellFolder
Dim hwnd As IntPtr
Dim bindContext As IBindCtx
Dim displayName As String
Dim refEaten As UInteger
Dim refPidl As PIDL
Dim refAttributes As ShellItemAttributesMask

instance.ParseDisplayName(hwnd, bindContext, 
	displayName, refEaten, refPidl, refAttributes)
```

**C++**<br />
``` C++
void ParseDisplayName(
	IntPtr hwnd, 
	[OptionalAttribute] [InAttribute] IBindCtx^ bindContext, 
	String^ displayName, 
	unsigned int% refEaten, 
	PIDL^% refPidl, 
	[InAttribute] [OutAttribute] ShellItemAttributesMask% refAttributes
)
```

**F#**<br />
``` F#
abstract ParseDisplayName : 
        hwnd : IntPtr * 
        [<OptionalAttribute>] bindContext : IBindCtx * 
        displayName : string * 
        refEaten : uint32 byref * 
        refPidl : PIDL byref * 
        refAttributes : ShellItemAttributesMask byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>hwnd</dt><dd>Type: System.IntPtr<br />A window handle. The client should provide a window handle if it displays a dialog or message box. Otherwise set *hwnd* to NULL.</dd><dt>bindContext (Optional)</dt><dd>Type: System.Runtime.InteropServices.ComTypes.IBindCtx<br />Optional. A pointer to a bind context used to pass parameters as inputs and outputs to the parsing function. 

 These passed parameters are often specific to the data source and are documented by the data source owners. For example, the file system data source accepts the name being parsed (as a WIN32_FIND_DATA structure), using the STR_FILE_SYS_BIND_DATA bind context parameter. 

 STR_PARSE_PREFER_FOLDER_BROWSING can be passed to indicate that URLs are parsed using the file system data source when possible. 

 Construct a bind context object using CreateBindCtx and populate the values using IBindCtx::RegisterObjectParam. 

 If no data is being passed to or received from the parsing function, this value can be NULL.</dd><dt>displayName</dt><dd>Type: System.String<br />A null-terminated Unicode string with the display name. 

 Because each Shell folder defines its own parsing syntax, the form this string can take may vary. 

 The desktop folder, for instance, accepts paths such as "C:\My Docs\My File.txt". 

 It also will accept references to items in the namespace that have a GUID associated with them using the "::{GUID}" syntax.</dd><dt>refEaten</dt><dd>Type: System.UInt32<br />A pointer to a value that receives the number of characters of the display name that was parsed. 

 If your application does not need this information, set *refEaten* to NULL, and no value will be returned.</dd><dt>refPidl</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />When this method returns, contains a pointer to the PIDL for the object. 

 The returned item identifier list specifies the item relative to the parsing folder. 

 If the object associated with *displayName* is within the parsing folder, the returned item identifier list will contain only one SHITEMID structure. 

 If the object is in a subfolder of the parsing folder, the returned item identifier list will contain multiple SHITEMID structures. 

 If an error occurs, NULL is returned in this address. 

 When it is no longer needed, it is the responsibility of the caller to free this resource by calling CoTaskMemFree.</dd><dt>refAttributes</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellItemAttributesMask">DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask</a><br />The value used to query for file attributes. 

 If not used, it should be set to NULL. To query for one or more attributes, initialize this parameter with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellItemAttributesMask">ShellItemAttributesMask</a> flags that represent the attributes of interest. On return, those attributes that are `true` (`True` in Visual Basic) and were requested will be set.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />