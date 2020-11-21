# Textfiles Class
 

Contains text-files related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Text.Tools.Textfiles<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class Textfiles : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class Textfiles
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As Textfiles
```

**C++**<br />
``` C++
public ref class Textfiles sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type Textfiles =  
    class
        inherit AestheticObject
    end
```

The Textfiles type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_Contains">Contains</a></td><td>
Determines whether the source textfile contains the specified string.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_CountAllLines">CountAllLines</a></td><td>
Gets the total amount of lines of the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_CountBlanktLines">CountBlanktLines</a></td><td>
Gets the total amount of blank lines of the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_CountNonBlanktLines">CountNonBlanktLines</a></td><td>
Gets the total amount of non-blank lines of the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_GetEncoding">GetEncoding(FileInfo)</a></td><td>
Determines the Encoding of the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_GetEncoding_1">GetEncoding(String)</a></td><td>
Determines the Encoding of the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_GetLine">GetLine</a></td><td>
Gets the specified line number from the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_GetLines">GetLines</a></td><td>
Gets the specified line numbers from the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_InsertLine">InsertLine(String, Int32, String, TextDirection, Encoding)</a></td><td>
Inserts the specified text-line in the given line number of the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_InsertLine_1">InsertLine(String, String, Int32, String, TextDirection, Encoding)</a></td><td>
Inserts the specified text-line in the given line number of the source textfile, then writes the result in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_InsertLines">InsertLines(String, Int32, IEnumerable(String), TextDirection, Encoding)</a></td><td>
Inserts the specified text-lines in the given line number of the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_InsertLines_1">InsertLines(String, String, Int32, IEnumerable(String), TextDirection, Encoding)</a></td><td>
Inserts the specified text-lines in the given line number of the source textfile, then writes the result in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_Randomize_1">Randomize(String, Encoding)</a></td><td>
Randomizes the lines of the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_Randomize">Randomize(String, String, Encoding)</a></td><td>
Randomizes the lines of the source textfile, then writes the result in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_RemoveLine">RemoveLine(String, Int32, TextDirection, Encoding)</a></td><td>
Removes the specified line number in the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_RemoveLine_1">RemoveLine(String, String, Int32, TextDirection, Encoding)</a></td><td>
Removes the specified line number in the source textfile, then writes the result in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_RemoveLines">RemoveLines(String, IEnumerable(Int32), TextDirection, Encoding)</a></td><td>
Removes the specified line numbers in the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_RemoveLines_1">RemoveLines(String, String, IEnumerable(Int32), TextDirection, Encoding)</a></td><td>
Removes the specified line numbers in the source textfile, then writes the result in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_ReplaceLine">ReplaceLine(String, Int32, IEnumerable(String), TextDirection, Encoding)</a></td><td>
Replaces the specified line number in the source textfile with the given text-lines.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_ReplaceLine_1">ReplaceLine(String, Int32, String, TextDirection, Encoding)</a></td><td>
Replaces the specified line number in the source textfile with the given text-line.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_ReplaceLine_2">ReplaceLine(String, String, Int32, IEnumerable(String), TextDirection, Encoding)</a></td><td>
Replaces the specified line number in the source textfile with the given text-lines, then writes the result in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_ReplaceLine_3">ReplaceLine(String, String, Int32, String, TextDirection, Encoding)</a></td><td>
Replaces the specified line number in the source textfile with the given text-line, then writes the result in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_ReplaceLines">ReplaceLines(String, IEnumerable(Int32), IEnumerable(String), TextDirection, Encoding)</a></td><td>
Replaces the specified line numbers in the source textfile with the given text-lines.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_ReplaceLines_1">ReplaceLines(String, IEnumerable(Int32), String, TextDirection, Encoding)</a></td><td>
Replaces the specified line numbers in the source textfile with the given text-line.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_ReplaceLines_2">ReplaceLines(String, String, IEnumerable(Int32), IEnumerable(String), TextDirection, Encoding)</a></td><td>
Replaces the specified line numbesr in the source textfile with the given text-line, then writes the result in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_ReplaceLines_3">ReplaceLines(String, String, IEnumerable(Int32), String, TextDirection, Encoding)</a></td><td>
Replaces the specified line numbesr in the source textfile with the given text-line, then writes the result in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_Reverse_1">Reverse(String, Encoding)</a></td><td>
Reverses the lines of the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_Reverse">Reverse(String, String, Encoding)</a></td><td>
Reverses the lines of the source textfile, then writes the result in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_SkipLines">SkipLines(String, Int32, TextDirection, Encoding)</a></td><td>
Skips the specified amount of lines in the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_SkipLines_1">SkipLines(String, String, Int32, TextDirection, Encoding)</a></td><td>
Skips the specified amount of lines in the source textfile, then writes the result in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_Sort">Sort(String, ListSortDirection, Encoding)</a></td><td>
Sorts the lines of the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_Sort_1">Sort(String, String, ListSortDirection, Encoding)</a></td><td>
Sorts the lines of the source textfile, then writes the result in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_SortBy__1">SortBy(T)(String, ListSortDirection, Func(String, T), Encoding)</a></td><td>
Sorts the lines of the source textfile by evaluating the result of the given condition.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_SortBy__1_1">SortBy(T)(String, String, ListSortDirection, Func(String, T), Encoding)</a></td><td>
Sorts the lines of the source textfile by evaluating the result of the given condition. then writes the result in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_Split">Split(String, Char, StringSplitOptions, Encoding)</a></td><td>
Splits the source textfile by the specified character.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_Split_1">Split(String, Char[], StringSplitOptions, Encoding)</a></td><td>
Splits the source textfile by the specified characters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_Split_2">Split(String, IEnumerable(String), StringSplitOptions, Encoding)</a></td><td>
Splits the source textfile by the specified strings.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_Split_3">Split(String, String, StringSplitOptions, Encoding)</a></td><td>
Splits the source textfile by the specified string.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_SplitByLines">SplitByLines</a></td><td>
Splits the source textfile by the specified amount of lines.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_TakeLines">TakeLines(String, Int32, TextDirection, Encoding)</a></td><td>
Takes the specified amount of lines from the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_TakeLines_1">TakeLines(String, String, Int32, TextDirection, Encoding)</a></td><td>
Takes the specified amount of lines from the source textfile, then writes the result in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_Trim">Trim(String, Char[], Encoding)</a></td><td>
Trims the specified chars in the lines of the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_Trim_1">Trim(String, String, Char[], Encoding)</a></td><td>
Trims the specified chars in the lines of the source textfile, then writes the result in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_TrimEnd">TrimEnd(String, Char[], Encoding)</a></td><td>
Trims the specified chars from the end of the lines of the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_TrimEnd_1">TrimEnd(String, String, Char[], Encoding)</a></td><td>
Trims the specified chars from the end of the lines of the source textfile, then writes the result in the target textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_TrimStart">TrimStart(String, Char[], Encoding)</a></td><td>
Trims the specified chars from the start of the lines of the source textfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_Textfiles_TrimStart_1">TrimStart(String, String, Char[], Encoding)</a></td><td>
Trims the specified chars from the start of the lines of the source textfile, then writes the result in the target textfile.</td></tr></table>&nbsp;
<a href="#textfiles-class">Back to Top</a>

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
<a href="#textfiles-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />