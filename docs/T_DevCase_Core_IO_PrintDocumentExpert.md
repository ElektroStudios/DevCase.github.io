# PrintDocumentExpert Class
 

Provides an advanced usage to print a text document.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.PrintDocumentExpert<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class PrintDocumentExpert : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public Class PrintDocumentExpert
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As PrintDocumentExpert
```

**C++**<br />
``` C++
public ref class PrintDocumentExpert : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
type PrintDocumentExpert =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The PrintDocumentExpert type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_PrintDocumentExpert__ctor">PrintDocumentExpert(String)</a></td><td>
Initializes a new instance of the PrintDocumentExpert class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_PrintDocumentExpert__ctor_1">PrintDocumentExpert(String, Encoding)</a></td><td>
Initializes a new instance of the PrintDocumentExpert class.</td></tr></table>&nbsp;
<a href="#printdocumentexpert-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_PrintDocumentExpert_BeginPrintEventHandler">BeginPrintEventHandler</a></td><td>
Gets or sets the PrintEventHandler delegate method to handle the BeginPrint event.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_PrintDocumentExpert_DocumentStream">DocumentStream</a></td><td>
Gets or sets the StreamReader instance that encapsulates the document data to be read and printed.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_PrintDocumentExpert_Encoding">Encoding</a></td><td>
Gets or sets the text encoding. 

 If no encoding is specified, the default system encoding will be used.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_PrintDocumentExpert_EndPrintEventHandler">EndPrintEventHandler</a></td><td>
Gets or sets the PrintEventHandler delegate method to handle the BeginPrint event.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_PrintDocumentExpert_Filepath">Filepath</a></td><td>
Gets the document file path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_PrintDocumentExpert_PrinterSettings">PrinterSettings</a></td><td>
Gets or sets the PrinterSettings instance that specifies information about how a document is printed, including the printer that prints it.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_PrintDocumentExpert_PrintPageEventHandler">PrintPageEventHandler</a></td><td>
Gets or sets the PrintPageEventHandler delegate method to handle the PrintPage event.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_PrintDocumentExpert_QueryPageSettingsEventHandler">QueryPageSettingsEventHandler</a></td><td>
Gets or sets the QueryPageSettingsEventHandler delegate method to handle the BeginPrint event.</td></tr></table>&nbsp;
<a href="#printdocumentexpert-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_PrintDocumentExpert_CancelPrint">CancelPrint</a></td><td>
Cancels the print job for the current document.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_PrintDocumentExpert_Dispose">Dispose</a></td><td>
Releases all the resources used by this <a href="T_DevCase_Core_IO_PrintDocumentBasic">PrintDocumentBasic</a> instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_PrintDocumentExpert_Print">Print</a></td><td>
Prints the current document.</td></tr></table>&nbsp;
<a href="#printdocumentexpert-class">Back to Top</a>

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
<a href="#printdocumentexpert-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Module Module1

    Private printExpert As PrintDocumentExpert

    Public Sub Main()

        printExpert = New PrintDocumentExpert("C:\Document.txt", Encoding.Default)

        Using printExpert
            printExpert.PrinterSettings = New PrinterSettings With {
                    .PrinterName = "My Printer Name"
                }

            printExpert.BeginPrintEventHandler = AddressOf PrintDocument_BeginPrint
            printExpert.QueryPageSettingsEventHandler = AddressOf PrintDocument_QueryPageSettings
            printExpert.PrintPageEventHandler = AddressOf PrintDocument_PrintPage
            printExpert.EndPrintEventHandler = AddressOf PrintDocument_EndPrint

            printExpert.Print()
        End Using

    End Sub

    Public Sub PrintDocument_BeginPrint(ByVal sender As Object, ByVal e As PrintEventArgs)
    End Sub

    Public Sub PrintDocument_QueryPageSettings(ByVal sender As Object, ByVal e As QueryPageSettingsEventArgs)
    End Sub

    Public Sub PrintDocument_PrintPage(ByVal sender As Object, ByVal e As PrintPageEventArgs)
        ' Page settings.
        Dim font As New Font("Arial", 10.0F, FontStyle.Regular)
        Dim brush As New SolidBrush(Color.Green)
        Dim stringFormat As New StringFormat()
        Dim leftMargin As Single = e.MarginBounds.Left
        Dim topMargin As Single = e.MarginBounds.Top

        ' Calculate the number of lines per page.
        Dim linesPerPage As Single = (e.MarginBounds.Height / font.GetHeight(e.Graphics))

        ' Iterate over the file, printing each line.
        Dim line As String = Nothing
        Dim count As Integer
        While (count < linesPerPage)
            line = printExpert.DocumentStream.ReadLine()
            If (line Is Nothing) Then
                Exit While
            End If
            Dim yPos As Single = (topMargin + count * font.GetHeight(e.Graphics))
            e.Graphics.DrawString(line, font, brush, leftMargin, yPos, stringFormat)
            count += 1
        End While

        font.Dispose()
        brush.Dispose()
        stringFormat.Dispose()

        ' If more lines exist, print another page.
        e.HasMorePages = (line IsNot Nothing)
    End Sub

    Public Sub PrintDocument_EndPrint(ByVal sender As Object, ByVal e As PrintEventArgs)
    End Sub

End Module
```


## Examples
This is a code example. 
**VB**<br />
``` VB
Public Sub Main()

    Dim printExpert As PrintDocumentExpert = Nothing

    Dim beginPrintEventHandler As PrintEventHandler =
        Sub(ByVal sender As Object, ByVal e As PrintEventArgs)
        End Sub

    Dim queryPageSettingsEventHandler As QueryPageSettingsEventHandler =
        Sub(ByVal sender As Object, ByVal e As QueryPageSettingsEventArgs)
        End Sub

    Dim printPageEventHandler As PrintPageEventHandler =
    Sub(ByVal sender As Object, ByVal e As PrintPageEventArgs)
        ' Page settings.
        Dim font As New Font("Arial", 10.0F, FontStyle.Regular)
        Dim brush As New SolidBrush(Color.Green)
        Dim stringFormat As New StringFormat()
        Dim leftMargin As Single = e.MarginBounds.Left
        Dim topMargin As Single = e.MarginBounds.Top

        ' Calculate the number of lines per page.
        Dim linesPerPage As Single = (e.MarginBounds.Height / font.GetHeight(e.Graphics))

        ' Iterate over the file, printing each line.
        Dim line As String = Nothing
        Dim count As Integer
        While (count < linesPerPage)
            line = printExpert.DocumentStream.ReadLine()
            If (line Is Nothing) Then
                Exit While
            End If
            Dim yPos As Single = (topMargin + count * font.GetHeight(e.Graphics))
            e.Graphics.DrawString(line, font, brush, leftMargin, yPos, stringFormat)
            count += 1
        End While

        font.Dispose()
        brush.Dispose()
        stringFormat.Dispose()

        ' If more lines exist, print another page.
        e.HasMorePages = (line IsNot Nothing)
    End Sub

    Dim endPrintEventHandler As PrintEventHandler =
        Sub(ByVal sender As Object, ByVal e As PrintEventArgs)
        End Sub

    printExpert = New PrintDocumentExpert("C:\Document.txt", Encoding.Default)
    Using printExpert
        printExpert.PrinterSettings = New PrinterSettings With {
            .PrinterName = "My Printer Name"
        }

        printExpert.BeginPrintEventHandler = beginPrintEventHandler
        printExpert.QueryPageSettingsEventHandler = queryPageSettingsEventHandler
        printExpert.PrintPageEventHandler = printPageEventHandler
        printExpert.EndPrintEventHandler = endPrintEventHandler

        printExpert.Print()
    End Using

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />System.IDisposable<br />