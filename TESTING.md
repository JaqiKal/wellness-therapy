#bugs while testing

240112 Bug01:
* Style.css
* The W3C CSS Validation Service, gives 1 Error (Parse Error) and 1 Warning (Imported style sheets are not checked in direct input and file upload modes.)
<!-- Add image -->
* Will revisit error and check code block by code block. 
* Warning is due the fact that W3C CSS Validator only validates the CSS code directly provided, not the code from external sources linked via @import rule to include external style sheets, specifically Google Fonts. This means that any CSS rules in the external style sheets are not being validated.