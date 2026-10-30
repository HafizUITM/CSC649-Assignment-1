# Part B3: User Stories and Acceptance Criteria

## User Story 1 (linked to FR2)
* **Story:** *As a* GAP digital investor, *I want to* enter a Ringgit amount into an instant calculator, *so that* I can immediately see how many grams of gold I am purchasing before committing.
* **Acceptance Criteria:**
  1. Entering a valid numeric value into the RM field auto-populates the Gram field within 100 milliseconds.
  2. Clearing the input field resets both currency and weight values to zero.

## User Story 2 (linked to FR4)
* **Story:** *As an* EPP installment buyer, *I want to* view a visual progress ring of my monthly payments, *so that* I can quickly track my remaining balance without calculating manual receipts.
* **Acceptance Criteria:**
  1. Clicking "EPP Center" displays all active installment contracts with completed percentages highlighted visually.
  2. Selecting an active plan reveals an itemized schedule showing paid dates and upcoming due dates.

## User Story 3 (linked to FR5)
* **Story:** *As a* physical gold buyer, *I want to* complete my order using direct payment options, *so that* my order is confirmed instantly without needing to manually upload bank payment slips.
* **Acceptance Criteria:**
  1. Selecting FPX/Direct Debit directs the user to automated confirmation upon payment completion.
  2. Order status automatically transitions from "Pending Payment" to "Processing" without admin slip review.
