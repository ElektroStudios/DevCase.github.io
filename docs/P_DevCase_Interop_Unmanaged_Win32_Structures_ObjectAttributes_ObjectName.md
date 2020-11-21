# ObjectAttributes.ObjectName Property 
 

Gets or sets a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_UnicodeString">UnicodeString</a> that contains the name of the object for which a handle is to be opened. 

 This must either be a fully qualified object name, or a relative path name to the directory specified by the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_RootDirectory">RootDirectory</a> member.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public UnicodeString ObjectName { get; set; }
```

**VB**<br />
``` VB
Public Property ObjectName As UnicodeString
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As ObjectAttributes
Dim value As UnicodeString

value = instance.ObjectName

instance.ObjectName = value
```

**C++**<br />
``` C++
public:
property UnicodeString ObjectName {
	UnicodeString get ();
	void set (UnicodeString value);
}
```

**F#**<br />
``` F#
member ObjectName : UnicodeString with get, set

```


#### Property Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_UnicodeString">UnicodeString</a><br />\[Missing <value> documentation for "P:DevCase.Interop.Unmanaged.Win32.Structures.ObjectAttributes.ObjectName"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes">ObjectAttributes Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />