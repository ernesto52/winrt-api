---
-api-id: T:Windows.Graphics.Printing.OptionDetails.PrintMediaTypeOptionDetails
-api-type: winrt class
-api-device-family-note: xbox
---

<!-- Class syntax.
public class PrintMediaTypeOptionDetails : Windows.Graphics.Printing.OptionDetails.IPrintItemListOptionDetails, Windows.Graphics.Printing.OptionDetails.IPrintOptionDetails
-->

# Windows.Graphics.Printing.OptionDetails.PrintMediaTypeOptionDetails

## -description
Represents the list of print media type options.

## -remarks
Here is a JavaScript code snippet that shows how to retrieve the object:





```javascript
//  Retrieve the advanced Print Task Options
var printDetailedOptions = 
     Windows.Graphics.Printing.OptionDetails.PrintTaskOptionDetails.getFromPrintTaskOptions(printTask.options);

// get the object
var printMediaTypeOptionDetails = 
     printDetailedOptions.options.lookup(Windows.Graphics.Printing.StandardPrintTaskOptions.mediaType);

```



## -examples

## -see-also