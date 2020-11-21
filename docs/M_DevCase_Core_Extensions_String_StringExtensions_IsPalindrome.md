# StringExtensions.IsPalindrome Method 
 

Determines whether the specified string is palindrome.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsPalindrome(
	this string sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsPalindrome ( 
	sender As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim returnValue As Boolean

returnValue = sender.IsPalindrome()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsPalindrome(
	String^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsPalindrome : 
        sender : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified string is palindrome; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Remarks
A palindrome is a word, phrase, number, or other sequence of characters which reads the same backward or forward. 

 Allowances may be made for adjustments to capital letters, punctuation, and word dividers. 

 For more info, see Wikipedia: <a href="http://en.wikipedia.org/wiki/Palindrome" target="_blank">http://en.wikipedia.org/wiki/Palindrome</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isPalindrome As Boolean = StringIsPalindrome("A man, a plan, a canal, Panama!")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />