# FileDater Class
 

Preserve, modify, truncate, and/or restore the date attributes of a file.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.FileDater<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class FileDater : AestheticObject, IDisposable
```

**VB**<br />
``` VB
Public Class FileDater
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileDater
```

**C++**<br />
``` C++
public ref class FileDater : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
type FileDater =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The FileDater type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileDater__ctor">FileDater(FileInfo)</a></td><td>
Initializes a new instance of the FileDater class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileDater__ctor_1">FileDater(String)</a></td><td>
Initializes a new instance of the FileDater class.</td></tr></table>&nbsp;
<a href="#filedater-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_FileDater_File">File</a></td><td>
Gets the file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_FileDater_SavedDate">SavedDate</a></td><td>
Gets a saved date.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_FileDater_SavedDateAttributes">SavedDateAttributes</a></td><td>
Gets the type of the current saved dates.</td></tr></table>&nbsp;
<a href="#filedater-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileDater_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileDater_Restore">Restore</a></td><td>
Restores the specified saved dates on the file. 

 Note: Calling this method does not cause the removal of any saved date.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileDater_Save">Save</a></td><td>
Preserves the specified dates of the file to restore them later at any time. 

 Note: Dates can be preserved again at any time.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileDater_Set">Set</a></td><td>
Sets the specified dates on the file. 

 Note: Calling this method does not cause the removal of any saved date. 

 After setting a date, must call once the <a href="M_DevCase_Core_IO_FileDater_Save">Save(DateAttribute)</a> method if want to save any date established.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileDater_SetFilepath">SetFilepath(FileInfo)</a></td><td>
Causes this FileDater instance to assign a new location for the current file. 

 This could be useful if the saved dates should be restored in a file that has changed its name/ubication. 

 Note: Calling this method does not cause the removal of any saved date.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileDater_SetFilepath_1">SetFilepath(String)</a></td><td>
Causes this FileDater instance to assign a new location for the current file. 

 This could be useful if the saved dates should be restored in a file that has changed its name/ubication. 

 Note: Calling this method does not cause the removal of any saved date.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileDater_Truncate">Truncate</a></td><td>
Truncates the specified date(s) of the file to "01/01/1800 00:00:00". 

 Note: Calling this method does not cause the removal of any saved date. 

 After setting a date, must call once the <a href="M_DevCase_Core_IO_FileDater_Save">Save(DateAttribute)</a> method if want to save any date established.</td></tr></table>&nbsp;
<a href="#filedater-class">Back to Top</a>

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
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#filedater-class">Back to Top</a>

## Examples
This is a code example that demonstrates how to save then restore the dates of a file. 
**VB**<br />
``` VB
Using fd As New FileDater("C:\File.txt")
    fd.Save(DateAttribute.Creation Or DateAttribute.Modification)

    File.AppendAllText("C:\File.txt", "Hello World!")

    fd.Restore(DateAttribute.Creation Or DateAttribute.Modification)
End Using
```


## Examples
This is a code example that demonstrates how to save then restore the dates of a file that has changed their ubication. 
**VB**<br />
``` VB
Using fd As New FileDater("C:\File.txt")

    ' Preserve all the current dates of the file.
    fd.Save(DateAttribute.All)

    ' Print the saved dates.
    Debug.WriteLine(String.Format("Saved Creation    Date: {0}", fd.SavedDate(DateAttribute.Creation).ToString()))
    Debug.WriteLine(String.Format("Saved Last-Access Date: {0}", fd.SavedDate(DateAttribute.Access).ToString()))
    Debug.WriteLine(String.Format("Saved Last-Modify Date: {0}", fd.SavedDate(DateAttribute.Modification).ToString()))

    ' Copy the file to other location.
    File.Copy(fd.File.FullName, "C:\New Testfile.tmp", overwrite:=True)

    ' Assign the new location in the FileDater instance.
    fd.SetFilepath("C:\New Testfile.tmp")

    ' Modify all the dates on the copied file.
    fd.Set(DateAttribute.All, Date.Parse("01/01/2015"))

    ' Restore all the previously saved dates on the copied file.
    fd.Restore(DateAttribute.All)

    ' Print the current dates of the copied file.
    Debug.WriteLine(String.Format("Saved Creation    Date: {0}", fd.File.CreationTime.ToString()))
    Debug.WriteLine(String.Format("Saved Last-Access Date: {0}", fd.File.LastAccessTime.ToString()))
    Debug.WriteLine(String.Format("Saved Last-Modify Date: {0}", fd.File.LastWriteTime.ToString()))

End Using
```


## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />