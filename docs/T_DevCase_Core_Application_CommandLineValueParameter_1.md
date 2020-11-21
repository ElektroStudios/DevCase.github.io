# CommandLineValueParameter(*T*) Class
 

Represents a command-line parameter that takes a value of specific Type.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Application_CommandLineParameter">DevCase.Core.Application.CommandLineParameter</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.CommandLineValueParameter(T)<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class CommandLineValueParameter<T> : CommandLineParameter
where T : IConvertible

```

**VB**<br />
``` VB
Public Class CommandLineValueParameter(Of T As IConvertible)
	Inherits CommandLineParameter
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineValueParameter(Of T)
```

**C++**<br />
``` C++
generic<typename T>
where T : IConvertible
public ref class CommandLineValueParameter : public CommandLineParameter
```

**F#**<br />
``` F#
type CommandLineValueParameter<'T when 'T : IConvertible> =  
    class
        inherit CommandLineParameter
    end
```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The Type of the value that the parameter takes.</dd></dl>&nbsp;
The CommandLineValueParameter(T) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1__ctor">CommandLineValueParameter(T)</a></td><td>
Initializes a new instance of the CommandLineValueParameter(T) class.</td></tr></table>&nbsp;
<a href="#commandlinevalueparameter(*t*)-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_CommandLineValueParameter_1_DefaultValue">DefaultValue</a></td><td>
Gets or sets the default parameter's value. 

 This value should be take into account if, after parsing the command-line arguments of the application, <a href="P_DevCase_Core_Application_CommandLineValueParameter_1_Value">Value</a> is a null reference (`Nothing` in Visual Basic), meaning that the end-user did not assigned any value to this parameter.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_CommandLineValueParameter_1_Suffix">Suffix</a></td><td>
Gets or sets the suffix character that delimits the parameter's name from the parameter's value. 

 For example: "/ParameterName=Value" where "/" is the prefix and "=" the suffix.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_CommandLineValueParameter_1_Value">Value</a></td><td>
Gets or sets the parameter's value defined by the end-user. 

 This value should be initially a null reference (`Nothing` in Visual Basic) before parsing the commandline arguments of the application. 

 The value of the parameter should be assigned by the end-user when passing an argument to the application. 

 To set a default value for this parameter, use <a href="P_DevCase_Core_Application_CommandLineValueParameter_1_DefaultValue">DefaultValue</a> property instead.</td></tr></table>&nbsp;
<a href="#commandlinevalueparameter(*t*)-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_GetSuffixChar">GetSuffixChar</a></td><td>
Gets the suffix character that delimits the parameter's name from the parameter's value. 

 For Example: "="</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_ToString">ToString</a></td><td>
Returns a String that represents this CommandLineValueParameter(T).</td></tr></table>&nbsp;
<a href="#commandlinevalueparameter(*t*)-class">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit">Implicit(CommandLineValueParameter(Boolean) to CommandLineValueParameter(T))</a></td><td>
Performs an implicit conversion from CommandLineValueParameter(T) to CommandLineValueParameter(T).</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit_1">Implicit(CommandLineValueParameter(Byte) to CommandLineValueParameter(T))</a></td><td>
Performs an implicit conversion from CommandLineValueParameter(T) to CommandLineValueParameter(T).</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit_2">Implicit(CommandLineValueParameter(Char) to CommandLineValueParameter(T))</a></td><td>
Performs an implicit conversion from CommandLineValueParameter(T) to CommandLineValueParameter(T).</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit_3">Implicit(CommandLineValueParameter(DateTime) to CommandLineValueParameter(T))</a></td><td>
Performs an implicit conversion from CommandLineValueParameter(T) to CommandLineValueParameter(T).</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit_4">Implicit(CommandLineValueParameter(Decimal) to CommandLineValueParameter(T))</a></td><td>
Performs an implicit conversion from CommandLineValueParameter(T) to CommandLineValueParameter(T).</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit_5">Implicit(CommandLineValueParameter(Double) to CommandLineValueParameter(T))</a></td><td>
Performs an implicit conversion from CommandLineValueParameter(T) to CommandLineValueParameter(T).</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit_6">Implicit(CommandLineValueParameter(IConvertible) to CommandLineValueParameter(T))</a></td><td>
Performs an implicit conversion from CommandLineValueParameter(T) to CommandLineValueParameter(T).</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit_7">Implicit(CommandLineValueParameter(Int16) to CommandLineValueParameter(T))</a></td><td>
Performs an implicit conversion from CommandLineValueParameter(T) to CommandLineValueParameter(T).</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit_8">Implicit(CommandLineValueParameter(Int32) to CommandLineValueParameter(T))</a></td><td>
Performs an implicit conversion from CommandLineValueParameter(T) to CommandLineValueParameter(T).</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit_9">Implicit(CommandLineValueParameter(Int64) to CommandLineValueParameter(T))</a></td><td>
Performs an implicit conversion from CommandLineValueParameter(T) to CommandLineValueParameter(T).</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit_10">Implicit(CommandLineValueParameter(SByte) to CommandLineValueParameter(T))</a></td><td>
Performs an implicit conversion from CommandLineValueParameter(T) to CommandLineValueParameter(T).</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit_11">Implicit(CommandLineValueParameter(Single) to CommandLineValueParameter(T))</a></td><td>
Performs an implicit conversion from CommandLineValueParameter(T) to CommandLineValueParameter(T).</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit_12">Implicit(CommandLineValueParameter(String) to CommandLineValueParameter(T))</a></td><td>
Performs an implicit conversion from CommandLineValueParameter(T) to CommandLineValueParameter(T).</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit_13">Implicit(CommandLineValueParameter(UInt16) to CommandLineValueParameter(T))</a></td><td>
Performs an implicit conversion from CommandLineValueParameter(T) to CommandLineValueParameter(T).</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit_14">Implicit(CommandLineValueParameter(UInt32) to CommandLineValueParameter(T))</a></td><td>
Performs an implicit conversion from CommandLineValueParameter(T) to CommandLineValueParameter(T).</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit_15">Implicit(CommandLineValueParameter(UInt64) to CommandLineValueParameter(T))</a></td><td>
Performs an implicit conversion from CommandLineValueParameter(T) to CommandLineValueParameter(T).</td></tr></table>&nbsp;
<a href="#commandlinevalueparameter(*t*)-class">Back to Top</a>

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
<a href="#commandlinevalueparameter(*t*)-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Module Module1

    Dim params As New CommandLineValueParameterCollection From {
        New CommandLineValueParameter(Of String)("ParameterName1") With {
            .Prefix = CommandLineParameterPrefix.Slash,
            .Suffix = CommandLineParameterSuffix.EqualsSign,
            .ShortName = "Param1",
            .DefaultValue = "",
            .IsOptional = False
        },
        New CommandLineValueParameter(Of Boolean)("ParameterName2") With {
            .Prefix = CommandLineParameterPrefix.Slash,
            .Suffix = CommandLineParameterSuffix.EqualsSign,
            .ShortName = "Param2",
            .DefaultValue = False,
            .IsOptional = True
        },
        New CommandLineValueParameter(Of Integer)("ParameterName3") With {
            .Prefix = CommandLineParameterPrefix.Slash,
            .Suffix = CommandLineParameterSuffix.EqualsSign,
            .ShortName = "Param3",
            .DefaultValue = -1I,
            .IsOptional = True
        }
    }

    Public Function IsParameterAssignedInArgument(Of T As IConvertible)(ByVal parameter As CommandLineValueParameter(Of T), ByVal argument As String) As Boolean
        Return (argument.StartsWith(parameter.FullName & parameter.GetSuffixChar(), StringComparison.OrdinalIgnoreCase) OrElse
                argument.StartsWith(parameter.FullShortName & parameter.GetSuffixChar(), StringComparison.OrdinalIgnoreCase))
    End Function

    Public Sub SetParameterValue(Of T As IConvertible)(ByRef parameter As CommandLineValueParameter(Of T), ByVal argument As String)

        If IsParameterAssignedInArgument(parameter, argument) Then

            Dim value As String = argument.Substring(argument.IndexOf(parameter.GetSuffixChar()) + 1).Trim(ControlChars.Quote)

            If String.IsNullOrEmpty(value) Then
                parameter.Value = parameter.DefaultValue

            Else
                Try
                    parameter.Value = DirectCast(Convert.ChangeType(value, parameter.DefaultValue.GetType()), T)

                Catch ex As InvalidCastException
                    Throw

                Catch ex As FormatException
                    Throw

                End Try

            End If

        End If

    End Sub

    Sub Main()

        ' Parse command-line arguments to set the values of the parameters.
        ParseArguments(params, AddressOf OnSyntaxError, AddressOf OnMissingParameterRequired)

        ' Display the parameters and each value assigned.
        For Each param As CommandLineValueParameter(Of IConvertible) In params
            Console.WriteLine(param.ToString())
        Next

    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Loop through all the command-line arguments of this application.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <param name="cmds">
    ''' The commandline parameters.
    ''' </param>
    '''
    ''' <param name="callbackSyntaxError">
    ''' An encapsulated method that is invoked if a syntax error is found in one of the arguments.
    ''' </param>
    '''
    ''' <param name="callbackMissingRequired">
    ''' An encapsulated method that is invoked if a required parameter is missing in the arguments.
    ''' </param>
    ''' ----------------------------------------------------------------------------------------------------
    Friend Sub ParseArguments(ByVal cmds As CommandLineValueParameterCollection,
                              ByVal callbackSyntaxError As Action(Of CommandLineValueParameter(Of IConvertible)),
                              ByVal callbackMissingRequired As Action(Of CommandLineValueParameter(Of IConvertible)))

        ParseArguments(cmds, Environment.GetCommandLineArgs.Skip(1), callbackSyntaxError, callbackMissingRequired)

    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Loop through all the command-line arguments of this application.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <param name="cmds">
    ''' The commandline parameters.
    ''' </param>
    '''
    ''' <param name="args">
    ''' The collection of commandline arguments to examine.
    ''' </param>
    '''
    ''' <param name="callbackSyntaxError">
    ''' An encapsulated method that is invoked if a syntax error is found in one of the arguments.
    ''' </param>
    '''
    ''' <param name="callbackMissingRequired">
    ''' An encapsulated method that is invoked if a required parameter is missing in the arguments.
    ''' </param>
    ''' ----------------------------------------------------------------------------------------------------
    Friend Sub ParseArguments(ByVal cmds As CommandLineValueParameterCollection,
                              ByVal args As IEnumerable(Of String),
                              ByVal callbackSyntaxError As Action(Of CommandLineValueParameter(Of IConvertible)),
                              ByVal callbackMissingRequired As Action(Of CommandLineValueParameter(Of IConvertible)))

        If Not (args.Any()) Then
            PrintHelp()
        End If

        ' Required parameters. Not optional ones.
        Dim cmdRequired As List(Of CommandLineValueParameter(Of IConvertible)) =
            (From cmd As CommandLineValueParameter(Of IConvertible) In cmds
             Where Not cmd.IsOptional).ToList()

        For Each arg As String In args

            For Each cmd As CommandLineValueParameter(Of IConvertible) In cmds

                If arg.Equals("/?") Then
                    PrintHelp()
                End If

                If IsParameterAssignedInArgument(cmd, arg) Then

                    If (cmdRequired.Contains(cmd)) Then
                        cmdRequired.Remove(cmd)
                    End If

                    Try
                        SetParameterValue(Of IConvertible)(cmd, arg)

                    Catch ex As Exception
                        callbackSyntaxError.Invoke(cmd)

                    End Try

                End If

            Next cmd

        Next arg

        If (cmdRequired.Any()) Then
            callbackMissingRequired.Invoke(cmdRequired.First())
        End If

    End Sub

    Friend Sub OnSyntaxError(ByVal cmd As CommandLineValueParameter(Of IConvertible))
        Console.WriteLine(String.Format("[X] Syntax error in parameter: {0})", cmd.FullName))
        Environment.Exit(exitCode:=1)
    End Sub

    Friend Sub OnMissingParameterRequired(ByVal cmd As CommandLineValueParameter(Of IConvertible))
        Console.WriteLine(String.Format("[X] Parameter {0} is required. ", cmd.FullName))
        Environment.Exit(exitCode:=1)
    End Sub

    Friend Sub PrintHelp()
        Dim sb As New Global.System.Text.StringBuilder
        sb.AppendLine("Commands Help:")
        For Each param As CommandLineValueParameter(Of IConvertible) In params
            sb.AppendFormat("{0} {{{1}}}", param.FullName, param.DefaultValue.GetType().Name)
            sb.AppendLine()
        Next
        Console.WriteLine(sb.ToString())
        Environment.Exit(exitCode:=1)
    End Sub

End Module
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />