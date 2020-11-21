# CommandLineArgumentsNotifier Class
 

Notifies when the current application receives new command-line arguments. 

 You would use this class to manage the command-line arguments for single-instance applications that are associated to filetypes, for example.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.CommandLineArgumentsNotifier<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class CommandLineArgumentsNotifier : AestheticObject, 
	INotifyPropertyChanged
```

**VB**<br />
``` VB
Public NotInheritable Class CommandLineArgumentsNotifier
	Inherits AestheticObject
	Implements INotifyPropertyChanged
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineArgumentsNotifier
```

**C++**<br />
``` C++
public ref class CommandLineArgumentsNotifier sealed : public AestheticObject, 
	INotifyPropertyChanged
```

**F#**<br />
``` F#
[<SealedAttribute>]
type CommandLineArgumentsNotifier =  
    class
        inherit AestheticObject
        interface INotifyPropertyChanged
    end
```

The CommandLineArgumentsNotifier type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineArgumentsNotifier__ctor">CommandLineArgumentsNotifier</a></td><td>
Initializes a new instance of the CommandLineArgumentsNotifier class.</td></tr></table>&nbsp;
<a href="#commandlineargumentsnotifier-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_CommandLineArgumentsNotifier_Arguments">Arguments</a></td><td>
Gets or sets the command-line arguments of the current application.</td></tr></table>&nbsp;
<a href="#commandlineargumentsnotifier-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")![Static member](media/static.gif "Static member")</td><td><a href="E_DevCase_Core_Application_CommandLineArgumentsNotifier_ArgumentsReceived">ArgumentsReceived</a></td><td>
Occurs when the application receives new command-line arguments.</td></tr></table>&nbsp;
<a href="#commandlineargumentsnotifier-class">Back to Top</a>

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
<a href="#commandlineargumentsnotifier-class">Back to Top</a>

## Explicit Interface Implementations
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private event](media/privevent.gif "Private event")</td><td><a href="E_DevCase_Core_Application_CommandLineArgumentsNotifier_System_ComponentModel_INotifyPropertyChanged_PropertyChanged">INotifyPropertyChanged.PropertyChanged</a></td><td /></tr></table>&nbsp;
<a href="#commandlineargumentsnotifier-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
' ----------------------------------------------------------------------------------------------------
' ApplicationEvents.vb
' ----------------------------------------------------------------------------------------------------
Imports Microsoft.VisualBasic.ApplicationServices

Namespace My

    Partial Friend Class MyApplication

        ''' <summary>
        ''' The <see cref="CommandLineArgumentsNotifier"/>.
        ''' </summary>
        Public Shared Notifier As CommandLineArgumentsNotifier

        ''' <summary>
        ''' Handles the <see cref="WindowsFormsApplicationBase.StartupNextInstance"/> event of <see cref="MyApplication"/>.
        ''' </summary>
        ''' <param name="sender">
        ''' The source of the event.
        ''' </param>
        ''' <param name="e">
        ''' The <see cref="StartupNextInstanceEventArgs"/> instance containing the event data.
        ''' </param>
        Public Sub MyApplication_StartupNextInstance(sender As Object, e As StartupNextInstanceEventArgs) Handles Me.StartupNextInstance

            ' If there are new command-line arguments, notify them.
            If (e.CommandLine.Any()) Then
                My.MyApplication.Notifier.Arguments = e.CommandLine
            End If

        End Sub

    End Class

End Namespace

' ----------------------------------------------------------------------------------------------------
' Form1.vb
' ----------------------------------------------------------------------------------------------------
Imports System.Collections.ObjectModel

Public Class Form1

    Public Sub New()
        MyClass.InitializeComponent()

        ' Associate the event before creating the instance, because we want to notify the current arguments of the application.
        AddHandler CommandLineArgumentsNotifier.ArgumentsReceived, AddressOf Me.CommandLineArgumentsNotifier_ArgumentsReceived

        ' Create an instance of CommandLineArgumentsNotifier and notify the current arguments of the application.
        My.MyApplication.Notifier = New CommandLineArgumentsNotifier(notifyCurrentArguments:=True)
    End Sub

    ''' <summary>
    ''' Handles the <see cref="CommandLineArgumentsNotifier.ArgumentsReceived"/> event of <see cref="My.MyApplication.Notifier"/>.
    ''' </summary>
    ''' <param name="sender">
    ''' The source of the event.
    ''' </param>
    ''' <param name="e">
    ''' The <see cref="CommandLineArgumentsEventArgs"/> instance containing the event data.
    ''' </param>
    Public Sub CommandLineArgumentsNotifier_ArgumentsReceived(sender As Object, e As CommandLineArgumentsEventArgs)

        ' In this example we add the new received command-line arguments to a existing ListBox control.
        Me.ListBox1.Items.AddRange(e.Arguments.ToArray())

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />System.ComponentModel.INotifyPropertyChanged<br />