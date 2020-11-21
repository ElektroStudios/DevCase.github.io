# CommandLineValueParameter(*T*) Properties
 

The <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> generic type exposes the following members.


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
<a href="#commandlinevalueparameter(*t*)-properties">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T) Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />