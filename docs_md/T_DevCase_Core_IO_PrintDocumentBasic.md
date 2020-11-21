# PrintDocumentBasic Class
 

Provides a basic usage to print a text document.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.PrintDocumentBasic<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class PrintDocumentBasic : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public Class PrintDocumentBasic
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As PrintDocumentBasic
```

**C++**<br />
``` C++
public ref class PrintDocumentBasic : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
type PrintDocumentBasic =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The PrintDocumentBasic type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_PrintDocumentBasic__ctor">PrintDocumentBasic(String)</a></td><td>
Initializes a new instance of the PrintDocumentBasic class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_PrintDocumentBasic__ctor_1">PrintDocumentBasic(String, Encoding)</a></td><td>
Initializes a new instance of the PrintDocumentBasic class.</td></tr></table>&nbsp;
<a href="#printdocumentbasic-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_PrintDocumentBasic_Color">Color</a></td><td>
Gets or sets the text color. 

 Default color is: Black</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_PrintDocumentBasic_Encoding">Encoding</a></td><td>
Gets or sets the text encoding. 

 If no encoding is specified, the default system encoding will be used.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_PrintDocumentBasic_Filepath">Filepath</a></td><td>
Gets the document file path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_PrintDocumentBasic_Font">Font</a></td><td>
Gets or sets the text font. 

 Default font is: [Font: Name=Arial, Size=10, Units=3, GdiCharSet=1, GdiVerticalFont=False]</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_PrintDocumentBasic_PrinterName">PrinterName</a></td><td>
Gets or sets the name of the printer device. 

 If no printer name is specified, the default printer device will be used.</td></tr></table>&nbsp;
<a href="#printdocumentbasic-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_PrintDocumentBasic_CancelPrint">CancelPrint</a></td><td>
Cancels the print job for the current document.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_PrintDocumentBasic_Dispose">Dispose</a></td><td>
Releases all the resources used by this PrintDocumentBasic instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_PrintDocumentBasic_Print">Print</a></td><td>
Prints the current document.</td></tr></table>&nbsp;
<a href="#printdocumentbasic-class">Back to Top</a>

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
<a href="#printdocumentbasic-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using printBasic As New PrintDocumentBasic("C:\Document.txt", Encoding.Default)
    printBasic.PrinterName = ""
    printBasic.Font = New Font("Arial", 10.0F, FontStyle.Regular)
    printBasic.Color = Color.Black

    printBasic.Print()
    ' printBasic.CancelPrint()
End Using
```


## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />System.IDisposable<br />