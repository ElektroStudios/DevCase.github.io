# SubtitleFile Class
 

Exposes the `SubtitleAPI.dll` functionalities in a friendly object to use with the specified subtitle file.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.SubtitleWorkshop.SubtitleFile<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_SubtitleWorkshop_LyricFile">DevCase.ThirdParty.SubtitleWorkshop.LyricFile</a><br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SubtitleWorkshop">DevCase.ThirdParty.SubtitleWorkshop</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class SubtitleFile : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public Class SubtitleFile
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As SubtitleFile
```

**C++**<br />
``` C++
public ref class SubtitleFile : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
type SubtitleFile =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The SubtitleFile type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile__ctor">SubtitleFile(FileInfo, Single)</a></td><td>
Initializes a new instance of the SubtitleFile class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile__ctor_1">SubtitleFile(String, Single)</a></td><td>
Initializes a new instance of the SubtitleFile class.</td></tr></table>&nbsp;
<a href="#subtitlefile-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile_File">File</a></td><td>
Gets the subtitle file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile_Format">Format</a></td><td>
Gets the subtitle format index of the current subtitle file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile_FormatName">FormatName</a></td><td>
Gets the subtitle format name of the current subtitle file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile_FPS">FPS</a></td><td>
Gets or sets the FPS of the current subtitle file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile_Lines">Lines</a></td><td>
Gets or sets the lines of the current subtitle file.</td></tr></table>&nbsp;
<a href="#subtitlefile-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile_Clear">Clear</a></td><td>
Clears all the subtitle lines in the current subtitle file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile_ConvertToFormat_1">ConvertToFormat(SubtitleFormat, String)</a></td><td>
Converts the current subtitle file to other subtitle format.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile_ConvertToFormat">ConvertToFormat(SubtitleFormat, Single, String)</a></td><td>
Converts the current subtitle file to other subtitle format.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile_Save">Save</a></td><td>
Saves all modifications to the current subtitle file.</td></tr></table>&nbsp;
<a href="#subtitlefile-class">Back to Top</a>

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
<a href="#subtitlefile-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using subtitle As New SubtitleFile("C:\file.lrc", 25)

    Console.WriteLine(String.Format("Format: {0}", CInt(subtitle.Format)))
    Console.WriteLine(String.Format("Format Name: {0}", subtitle.FormatName))

    ' Insert a subtitle line.
    subtitle.Lines.Insert(1, New SubtitleLine(1, 1000, 2000, "Hello World!"))

    ' Save the modifications in the current file.
    subtitle.Save()

    ' Convert the subtitle format.
    subtitle.ConvertToFormat(SubtitleFormat.SubRip, "C:\New.srt")

End Using
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_SubtitleWorkshop">DevCase.ThirdParty.SubtitleWorkshop Namespace</a><br />