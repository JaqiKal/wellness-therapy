#bugs while testing

## 240112 Bug01:
* Style.css
* The W3C CSS Validation Service, gives 1 Error (Parse Error) and 1 Warning (Imported style sheets are not checked in direct input and file upload modes.)
<!-- Add image -->
* Will revisit error and check code block by code block. 
* Warning is due the fact that W3C CSS Validator only validates the CSS code directly provided, not the code from external sources linked via @import rule to include external style sheets, specifically Google Fonts. This means that any CSS rules in the external style sheets are not being validated.

## 240113 Bug02:
*'Attribute class:'logo-img' is not serializable as XML 1.0', used colon instead of =.
In a class attribute for logo-img.

## 240113 Bug03:
* Warning: Attribute dropbtn" is not serializable as XML 1.0.
* Missing quote on attribute dropbtn.

## 240113 Bug04:
* Warning: Section lacks heading.
* added heading in the sections.