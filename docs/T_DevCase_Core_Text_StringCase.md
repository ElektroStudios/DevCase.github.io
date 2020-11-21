# StringCase Enumeration
 

Specifies a string case.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum StringCase
```

**VB**<br />
``` VB
Public Enumeration StringCase
```

**VB Usage**<br />
``` VB Usage
Dim instance As StringCase
```

**C++**<br />
``` C++
public enum class StringCase
```

**F#**<br />
``` F#
type StringCase
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.Text.StringCase.LowerCase">**LowerCase**</td><td>0</td><td>LowerCase 

 [Example] 

 Input : ABCDEF 

 Output: abcdef</td></tr><tr><td /><td target="F:DevCase.Core.Text.StringCase.UpperCase">**UpperCase**</td><td>1</td><td>UpperCase. 

 [Example] 

 Input : abcdef 

 Output: ABCDEF</td></tr><tr><td /><td target="F:DevCase.Core.Text.StringCase.TitleCase">**TitleCase**</td><td>2</td><td>TitleCase. 

 [Example] 

 Input : abcdef 

 Output: Abcdef</td></tr><tr><td /><td target="F:DevCase.Core.Text.StringCase.WordCase">**WordCase**</td><td>3</td><td>WordCase. 

 [Example] 

 Input : abc def 

 Output: Abc Def</td></tr><tr><td /><td target="F:DevCase.Core.Text.StringCase.CamelCaseLower">**CamelCaseLower**</td><td>4</td><td>CamelCase (With first letter to LowerCase). 

 [Example] 

 Input : ABC DEF 

 Output: abcDef</td></tr><tr><td /><td target="F:DevCase.Core.Text.StringCase.CamelCaseUpper">**CamelCaseUpper**</td><td>5</td><td>CamelCase (With first letter to UpperCase). 

 [Example] 

 Input : ABC DEF 

 Output: AbcDef</td></tr><tr><td /><td target="F:DevCase.Core.Text.StringCase.MixedTitleCaseLower">**MixedTitleCaseLower**</td><td>6</td><td>MixedCase (With first letter to LowerCase). 

 [Example] 

 Input : ab cd ef 

 Output: aB Cd eF</td></tr><tr><td /><td target="F:DevCase.Core.Text.StringCase.MixedTitleCaseUpper">**MixedTitleCaseUpper**</td><td>7</td><td>MixedCase (With first letter to UpperCase). 

 [Example] 

 Input : ab cd ef 

 Output: Ab cD Ef</td></tr><tr><td /><td target="F:DevCase.Core.Text.StringCase.MixedWordCaseLower">**MixedWordCaseLower**</td><td>8</td><td>MixedCase (With first letter of each word to LowerCase). 

 [Example] 

 Input : ab cd ef 

 Output: aB cD eF</td></tr><tr><td /><td target="F:DevCase.Core.Text.StringCase.MixedWordCaseUpper">**MixedWordCaseUpper**</td><td>9</td><td>MixedCase (With first letter of each word to UpperCase). 

 [Example] 

 Input : ab cd ef 

 Output: Ab Cd Ef</td></tr><tr><td /><td target="F:DevCase.Core.Text.StringCase.ToggleCase">**ToggleCase**</td><td>16</td><td>ToggleCase. 

 [Example] 

 Input : abc def ghi 

 Output: aBC dEF gHI</td></tr><tr><td /><td target="F:DevCase.Core.Text.StringCase.DuplicateChars">**DuplicateChars**</td><td>17</td><td>Duplicates the characters. 

 [Example] 

 Input : Hello World! 

 Output: HHeelllloo WWoorrlldd!!</td></tr><tr><td /><td target="F:DevCase.Core.Text.StringCase.AlternateChars">**AlternateChars**</td><td>18</td><td>Alternates the characters. 

 [Example] 

 Input : Hello World! 

 Output: hELLO wORLD!</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />