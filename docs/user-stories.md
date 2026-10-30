# User Stories

## US1 - Calculate gold gram equivalent (FR2)

As a GAP digital investor, I want to enter a Ringgit amount into an instant calculator, so that I can see how many grams of gold I am purchasing before committing.

Acceptance criteria:

1. Given that I enter a valid numeric Ringgit amount, when the value changes, then the system calculates and displays the equivalent gold weight in grams within 100 milliseconds based on the live spot rate.
2. Given that I clear the Ringgit input field or enter 0, when the calculation updates, then the system resets both currency and weight values to zero without errors.
3. Given that I enter a negative number or invalid non-numeric text, when I submit or leave the field, then the system rejects the input and displays a clear error message.

---

## US2 - Track EPP installment progress (FR4)

As an EPP installment buyer, I want to view a visual completion progress ring for my active plans, so that I can quickly track my remaining balance without calculating manual receipts.

Acceptance criteria:

1. Given that I navigate to the EPP Management Center, when my active contracts load, then I can see a visual progress ring showing the completed payment percentage (e.g., "Month 4 of 10 Paid — 40%").
2. Given that I select a specific active EPP plan, when its details panel opens, then I can see an itemized payment schedule stating paid dates, upcoming due dates, and remaining monthly amounts.

---

## US3 - Complete automated gateway payment (FR5)

As a physical gold buyer, I want to pay using direct online payment options (FPX or e-Wallet), so that my order is approved instantly without uploading manual bank payment slips.

Acceptance criteria:

1. Given that I select FPX direct debit or e-Wallet at checkout, when my payment is confirmed by the gateway, then the system updates the order status from "Pending Payment" to "Processing" automatically.
2. Given that an FPX transaction fails or is canceled by the user, when the system receives the gateway response, then it retains the item in the cart and displays a payment failed alert with a retry button.
