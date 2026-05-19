# McDonald's Mobile App - Test Cases

| Test Case ID | Feature | Test Scenario | Preconditions | Test Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|
| TC-001 | App Launch | Verify app opens successfully | App installed | Open the app | App should launch without crashing | As expected | Pass |
| TC-002 | Login | Verify login with valid credentials | User has account | Enter valid email/password and tap Login | User should log in successfully | As expected | Pass |
| TC-003 | Login | Verify login with invalid password | User has account | Enter valid email and wrong password | Error message should appear | As expected | Pass |
| TC-004 | Menu | Verify menu items are displayed | App opened | Go to Menu section | Menu items should display correctly | As expected | Pass |
| TC-005 | Cart | Verify item can be added to cart | Menu available | Select item and tap Add to Cart | Item should appear in cart | As expected | Pass |
| TC-006 | Cart | Verify item quantity can be changed | Item in cart | Increase/decrease quantity | Quantity and price should update | As expected | Pass |
| TC-007 | Location | Verify nearby restaurants are shown | Location permission enabled | Open location/store finder | Nearby restaurants should display | As expected | Pass |
| TC-008 | Checkout | Verify checkout page opens | Item in cart | Tap checkout | Checkout page should open | As expected | Pass |
| TC-009 | UI | Verify buttons and text are visible | App opened | Check main screens | Buttons/text should be clear and aligned | As expected | Pass |
| TC-010 | Smoke Test | Verify main user flow works | App installed | Open app → view menu → add item → cart | Main flow should work without major issue | As expected | Pass |
