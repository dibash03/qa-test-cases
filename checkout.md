| Test Case ID | Title | Steps summary | Actual Result | Status |
|---|---|---|---|---|
| TC_CHECKOUT_001 | Complete checkout with valid info | Go to Cart, click Checkout, enter First/Last Name + Postal Code, click Continue, click Finish | Confirmation message shown | pass |
| TC_CHECKOUT_002 | Missing First Name| Leave First Name empty, fill Last Name + Postal Code, click Continue | Error message shown: "First Name is required" | pass |
| TC_CHECKOUT_003 | Missing last name | Fill First Name empty, leave Last Name,  fill Postal Code, click Continue | Error message shown: "Last Name is required" | pass |
| TC_CHECKOUT_004 | Missing postal code | Fill First Name and Last Name,  leave Postal Code empty, click Continue | Error message shown: "Postal code is required" | pass |
| TC_CHECKOUT_005 | Order summary totals are accurate | Add 2-3 items, go to Overview page, check Item total + Tax + Total | Item total, tax line, and total all shown correctly | pass |
| TC_CHECKOUT_006 | Cancel returns to products page |  Click Cancel from Checkout Information/Overview page with items in cart | Returned to Products page, cart items still intact | pass |

