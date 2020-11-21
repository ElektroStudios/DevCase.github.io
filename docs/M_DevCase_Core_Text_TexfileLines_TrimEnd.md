# TexfileLines.TrimEnd Method 
 

Removes all trailing occurrences of a set of characters from all the elements of this <a href="T_DevCase_Core_Text_TexfileLines">TexfileLines</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void TrimEnd(
	char[] trimChars = null
)
```

**VB**<br />
``` VB
Public Overridable Sub TrimEnd ( 
	Optional trimChars As Char() = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As TexfileLines
Dim trimChars As Char()

instance.TrimEnd(trimChars)
```

**C++**<br />
``` C++
public:
virtual void TrimEnd(
	array<wchar_t>^ trimChars = nullptr
)
```

**F#**<br />
``` F#
abstract TrimEnd : 
        ?trimChars : char[] 
(* Defaults:
        let _trimChars = defaultArg trimChars null
*)
-> unit 
override TrimEnd : 
        ?trimChars : char[] 
(* Defaults:
        let _trimChars = defaultArg trimChars null
*)
-> unit 
```


#### Parameters
&nbsp;<dl><dt>trimChars (Optional)</dt><dd>Type: System.Char[]<br />An array of Unicode characters to remove. 

 If *trimChars* is a null reference (`Nothing` in Visual Basic) or an empty array, Unicode white-space characters are removed instead.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Text_TexfileLines">TexfileLines Class</a><br /><a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />