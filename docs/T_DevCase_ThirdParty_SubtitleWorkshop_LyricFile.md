# LyricFile Class
 

Exposes the `SubtitleAPI.dll` functionalities in a friendly object to use with the specified lyric file.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile">DevCase.ThirdParty.SubtitleWorkshop.SubtitleFile</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.SubtitleWorkshop.LyricFile<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SubtitleWorkshop">DevCase.ThirdParty.SubtitleWorkshop</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class LyricFile : SubtitleFile
```

**VB**<br />
``` VB
Public NotInheritable Class LyricFile
	Inherits SubtitleFile
```

**VB Usage**<br />
``` VB Usage
Dim instance As LyricFile
```

**C++**<br />
``` C++
public ref class LyricFile sealed : public SubtitleFile
```

**F#**<br />
``` F#
[<SealedAttribute>]
type LyricFile =  
    class
        inherit SubtitleFile
    end
```

The LyricFile type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SubtitleWorkshop_LyricFile__ctor">LyricFile(FileInfo)</a></td><td>
Initializes a new instance of the LyricFile class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SubtitleWorkshop_LyricFile__ctor_1">LyricFile(String)</a></td><td>
Initializes a new instance of the LyricFile class.</td></tr></table>&nbsp;
<a href="#lyricfile-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_SubtitleWorkshop_LyricFile_Format">Format</a></td><td>
Gets the subtitle format index of the current subtitle file.
 (Overrides <a href="P_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile_Format">SubtitleFile.Format</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_SubtitleWorkshop_LyricFile_FormatName">FormatName</a></td><td>
Gets the subtitle format name of the current subtitle file.
 (Overrides <a href="P_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile_FormatName">SubtitleFile.FormatName</a>.)</td></tr></table>&nbsp;
<a href="#lyricfile-class">Back to Top</a>

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
<a href="#lyricfile-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using lyric As New LyricFile("C:\File.lrc")

    Console.WriteLine(String.Format("Format: {0}", CInt(lyric.Format)))
    Console.WriteLine(String.Format("Format Name: {0}", lyric.FormatName))

    ' Insert a subtitle line.
    lyric.Lines.Insert(1, New LyricLine(1, 1000, 2000, "Hello World!"))

    ' Save the modifications in the current file.
    lyric.Save()

    ' Convert the subtitle format.
    lyric.ConvertToFormat(SubtitleFormat.SubRip, "C:\New.srt")

End Using
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_SubtitleWorkshop">DevCase.ThirdParty.SubtitleWorkshop Namespace</a><br />