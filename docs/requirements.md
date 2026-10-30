# Part B: Requirements Specification

## B1. Functional Requirements (FRs)

| ID | Requirement Statement | Testability Criteria |
| :--- | :--- | :--- |
| **FR1** | The system shall display a live gold spot price ticker pinned to the top navigation header across all pages. | Verify that gold spot rates refresh automatically every 180 seconds with visible trend color indicators (green/red). |
| **FR2** | The system shall provide an interactive currency-to-weight converter for GAP top-ups. | Inputting a Ringgit amount (e.g., RM 100) must immediately calculate and display the exact gold gram equivalent based on the current rate. |
| **FR3** | The system shall provide a unified asset dashboard displaying both digital GAP balances and physical vaulted inventory on a single screen. | Verify that the portfolio summary page separates digital weight from vaulted physical bars clearly. |
| **FR4** | The system shall display a visual progress bar for all active EPP installment plans. | The user account page must accurately show completed vs. remaining payments (e.g., "Month 4 of 10 Paid — 40%"). |


## B2. Non-Functional Requirements (NFRs)

| ID | Type | Requirement Statement | Measurable Target |
| :--- | :--- | :--- | :--- |
| **NFR1** | Usability | The platform interface shall adhere to AA accessibility contrast ratios for all critical transaction buttons and price text. | Minimum contrast ratio of 4.5:1 against dark/light backgrounds verified via WCAG guidelines. |
| **NFR2** | Performance | The high-fidelity dashboard prototype components shall render interactive charts within a target loading threshold. | Interactive price history graphs load complete vector data in under 1.5 seconds. |
| **NFR3** | Reliability | The responsive mobile viewport layout shall maintain functional touch targets without horizontal layout breaking across standard mobile screen widths. | Zero horizontal scrollbars triggered on viewports between 360px and 430px wide. |
