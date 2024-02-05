#### Description of markup format

Elements are indicated by the use of a case sensitive name starting with a character which is neither a symbol nor a digit (0 to 9), with digits being allowed in the following characters of the name. In addition names may contain underline characters (“_”) in any position and dash or hyphen minus (“-”) characters but not as the first character. Attributes follow the same naming rules as for elements but are proceeded by the dollar (“$”) symbol. 

Elements may contain text data and also may contain attributes and other elements. Attributes may only contain text content. There are no standard rules in XML as to when attributes should be used rather than elements.

The main control symbols used in a markup tag are Level indicators – which must be before any other symbols used. Level indicators are a single “-” symbol to indicate down one level and “+” symbols to indicate up one or more levels. Level indicators must not be used before attributes as these always “belong” to the preceding element.

Other control symbols used are type symbols which include “$” for attributes plus “!” for XML comments and “?” for processing instructions. In addition there are substitution symbols which include “*” to indicate repeating the previous element name at this level.

The text content for an element or attribute follows the markup tag for this. Where an element has attributes these must follow the text content for the element. Where an element contains other elements the first of these elements must specify that it is one level down. When all the elements contained within another element have been given then “+” control symbols must be used before the first element at the higher level.

An example of these is:


**Students:** <br>
        **Student:         $Number:** 3671 <br>
                **−Name:** <br>
                        **−Given:** Charlie         **Last:** Doe <br>
                **+Location: ** <br>
                        **−Building:** Block B         **Class:** 12A <br>

<details>
<summary> Expand for Conversion to XML </summary>
**ᐸStudentsᐳ** <br>
        **ᐸStudent Number=”3671” ᐳ** <br>
                **ᐸNameᐳ** <br>
                        **ᐸGivenᐳ**Charlie**ᐸ/Givenᐳ** <br>
                        **ᐸLastᐳ **Doe**ᐸ/Lastᐳ** <br>
                **ᐸLocationᐳ ** <br>
                        **ᐸBuildingᐳ**Block B**ᐸ/Buildingᐳ** <br>
                        **ᐸClassᐳ**12A**ᐸ/Classᐳ** <br>
</details>

There are some complexities inherent in XML which will not often be relevant or required but in some cases can be essential. These include namespaces, inter-element text, processing instructions, XML comments, XML declarations, DOCTYPE declarations and Unicode considerations. 

These are covered in further sections. In addition Full details can be found in the relevant specifications:
* [Extensible Markup Language (XML) 1.1](https://www.w3.org/TR/xml11/)
* [Namespaces in XML 1.0](https://www.w3.org/TR/xml-names/) 
* [The Unicode Standard Version 15.0 ](https://www.unicode.org/versions/Unicode15.0.0/UnicodeStandard-15.0.pdf)

This is not a specification - but where used the emphasised words **"Must", "Must not", "Required", "Shall", "Shall not", "Should", "Should not", "Recommended",  "May", and "Optional"** have the meanings as described in RFC 2119. Where definitions of grammar are given these use the XML Extended Backus-Naur Form (EBNF) notation.
