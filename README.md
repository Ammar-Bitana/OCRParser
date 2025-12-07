# OCRParser

- **What it does**

Reads incoming scan text from 
**Daily SF Stock Google Sheet-scans**

Automatically extracts:
-Scan ID

-Service Name

-Username

-Timestamp Scanned

- Scanned values from the OCR and parses it into:
  
    -PC Quantity
  
    -Extrusion Date
  
    -Expiry Date
  
    -Mfg Date
  
    -Batch/Lot Number
  
    -IDH/Product ID

Lastly detects question / answer pairs dynamically, converts questions into new column headers, and fills corresponding answers per scan.
