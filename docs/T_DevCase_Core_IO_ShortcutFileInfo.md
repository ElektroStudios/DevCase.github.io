# ShortcutFileInfo Class
 

Provides information about a shortcut (.lnk) file.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.IO.FileSystemInfo<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.ShortcutFileInfo<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("ShortcutFileInfo")]
[TypeConverterAttribute(typeof(ExpandableObjectConverter))]
[DefaultPropertyAttribute("Target")]
public sealed class ShortcutFileInfo : FileSystemInfo
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("ShortcutFileInfo")>
<TypeConverterAttribute(GetType(ExpandableObjectConverter))>
<DefaultPropertyAttribute("Target")>
Public NotInheritable Class ShortcutFileInfo
	Inherits FileSystemInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShortcutFileInfo
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"ShortcutFileInfo")]
[TypeConverterAttribute(typeof(ExpandableObjectConverter))]
[DefaultPropertyAttribute(L"Target")]
public ref class ShortcutFileInfo sealed : public FileSystemInfo
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("ShortcutFileInfo")>]
[<TypeConverterAttribute(typeof(ExpandableObjectConverter))>]
[<DefaultPropertyAttribute("Target")>]
type ShortcutFileInfo =  
    class
        inherit FileSystemInfo
    end
```

The ShortcutFileInfo type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo__ctor">ShortcutFileInfo(FileInfo)</a></td><td>
Initializes a new instance of the ShortcutFileInfo class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo__ctor_1">ShortcutFileInfo(String)</a></td><td>
Initializes a new instance of the ShortcutFileInfo class.</td></tr></table>&nbsp;
<a href="#shortcutfileinfo-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_ShortcutFileInfo_Description">Description</a></td><td>
Gets or sets the shortcut description.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_ShortcutFileInfo_FullName">FullName</a></td><td>
Gets the full path of the shortcut file.
 (Overrides FileSystemInfo.FullName.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_ShortcutFileInfo_Hotkey">Hotkey</a></td><td>
Gets or sets the shortcut hotkey.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_ShortcutFileInfo_Icon">Icon</a></td><td>
Gets or sets the full path of the icon file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_ShortcutFileInfo_IconIndex">IconIndex</a></td><td>
Gets or sets the image index within the icon file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_ShortcutFileInfo_Length">Length</a></td><td>
Gets the file size, in bytes, of the current shortcut file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_ShortcutFileInfo_Name">Name</a></td><td>
Gets the file name of the shortcut file.
 (Overrides FileSystemInfo.Name.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_ShortcutFileInfo_Target">Target</a></td><td>
Gets or sets the full path of the target file or directory.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_ShortcutFileInfo_TargetArguments">TargetArguments</a></td><td>
Gets or sets the command-line arguments of the target.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_ShortcutFileInfo_TargetDisplayName">TargetDisplayName</a></td><td>
Gets the display name of the target file or directory. 

 Returns a empty string if the target does not exist.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_ShortcutFileInfo_WindowState">WindowState</a></td><td>
Gets or sets the window state for the target file or directory.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_ShortcutFileInfo_WorkingDirectory">WorkingDirectory</a></td><td>
Gets or sets the working directory of the target file or directory.</td></tr></table>&nbsp;
<a href="#shortcutfileinfo-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_CopyTo">CopyTo</a></td><td>
Copies an existing shortcut file to a new file, allowing the overwriting of an existing file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Create">Create</a></td><td>
Creates the shortcut file. It overwrites any existing file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Decrypt">Decrypt</a></td><td>
Decrypts a shortcut file that was encrypted by the current account using the <a href="M_DevCase_Core_IO_ShortcutFileInfo_Encrypt">Encrypt()</a> method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Delete">Delete</a></td><td>
Deletes the shortcut file.
 (Overrides FileSystemInfo.Delete().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Encrypt">Encrypt</a></td><td>
Encrypts a shortcut file so that only the account used to encrypt the file can decrypt it.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Equals">Equals</a></td><td>
Determines whether the specified ShortcutFileInfo is equal to this ShortcutFileInfo.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_GetAccessControl">GetAccessControl()</a></td><td>
Gets a FileSecurity object that encapsulates the access control list (ACL) entries for the file described by the current ShortcutFileInfo object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_GetAccessControl_1">GetAccessControl(AccessControlSections)</a></td><td>
Gets a FileSecurity object that encapsulates the specified type of access control list (ACL) entries for the file described by the current ShortcutFileInfo object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_MoveTo">MoveTo</a></td><td>
Moves the shortcut file to a new location, providing the option to specify a new file name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Open">Open(FileMode)</a></td><td>
Opens the shortcut file in the specified mode.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Open_1">Open(FileMode, FileAccess)</a></td><td>
Opens the shortcut file in the specified mode with read, write, or read/write access.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Open_2">Open(FileMode, FileAccess, FileShare)</a></td><td>
Opens the shortcut file in the specified mode with read, write, or read/write access and the specified sharing option.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_OpenRead">OpenRead</a></td><td>
Creates a read-only FileStream.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_OpenWrite">OpenWrite</a></td><td>
Creates a write-only FileStream.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Refresh">Refresh</a></td><td>
Refreshes the state of the object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Resolve">Resolve</a></td><td>
Resolves the target of a shortcut. 

 This is useful when the target of a shortcut file is changed from a drive letter to another, for example. 

 If the target can't be resolved, an error message would be displayed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_ToString">ToString</a></td><td>
Returns the shortcut' path as a string.
 (Overrides Object.ToString().)</td></tr></table>&nbsp;
<a href="#shortcutfileinfo-class">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_op_Equality">Equality</a></td><td>
Determines whether the specified ShortcutFileInfo instances are equal.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_op_Implicit_1">Implicit(FileInfo to ShortcutFileInfo)</a></td><td>
Performs an implicit conversion from FileInfo to ShortcutFileInfo.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_op_Implicit">Implicit(ShortcutFileInfo to FileInfo)</a></td><td>
Performs an implicit conversion from ShortcutFileInfo to FileInfo.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_op_Inequality">Inequality</a></td><td>
Determines whether the specified ShortcutFileInfo instances are not equal.</td></tr></table>&nbsp;
<a href="#shortcutfileinfo-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_FileSystemInfo_FileSystemInfoExtensions_GetFileHandle">GetFileHandle</a></td><td>
Gets a file handle for the specified file or directory.
 (Defined by <a href="T_DevCase_Core_Extensions_FileSystemInfo_FileSystemInfoExtensions">FileSystemInfoExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#shortcutfileinfo-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim lnk As New ShortcutFileInfo("C:\Test Shortcut.lnk")
lnk.Create()

With lnk
    .Attributes = FileAttributes.Normal
    .Description = "My shortcut description."
    .Hotkey = Keys.Shift Or Keys.Alt Or Keys.Control Or Keys.F1
    .Icon = "Shell32.dll"
    .IconIndex = 0
    .Target = "C:\Windows\Notepad.exe"
    .TargetArguments = """C:\Windows\win.ini"""
    .WindowState = ShortcutWindowState.Normal
    .WorkingDirectory = Path.GetDirectoryName(lnk.Target)
End With

lnk.ViewMode = True
Me.PropertyGrid1.SelectedObject = lnk
```


## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />