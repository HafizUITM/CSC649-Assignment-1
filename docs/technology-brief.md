# Part C: Specialized Technology Brief

## C1. Fundamental Concepts
Unified UX Architecture and Design System

UX architecture is the structure that organizes an interface’s content, navigation, and interactions so users can complete tasks with less effort. In fintech, it combines three ideas:

* **Visual hierarchy:** Information is grouped into clear zones so the most important items, such as the live gold price and the main action button, are seen first.
* **Cognitive load reduction:** Users should not have to remember or work out what to do next. This is achieved by reducing task depth (the number of steps needed to finish a task) and keeping related functions together.
* **Interaction feedback:** Micro-interactions, such as a price change animation or a payment status message, tell users immediately that the system has responded to their action.

A Design System supports this by providing reusable components, colors, typography, and spacing rules, so every screen behaves consistently. Together, they are expected to support faster decisions and greater trust on a platform where gold prices change frequently.

## C2. Frameworks, Models, Methods, and Tools
1. **Goal-Directed Design (GDD):** A framework built around user personas and context scenarios. It maps each user goal to a specific interface element, which helps prevent feature bloat.
2. **Heuristic Evaluation (Nielsen’s 10 Usability Heuristics):** Used to audit the current Public Gold interface and identify problems in navigation, feedback, and visibility of system status.
3. **Fishbone Diagram:** Used to trace the root causes of friction, such as clutter, fragmented modules, and manual payment verification.
4. **Card Sorting and Tree Testing:** Used to validate the restructured Information Architecture and confirm that users can find GAP, EPP, and bullion catalog functions.
5. **Figma and Design System components:** An industry-standard prototyping tool used to enforce consistency through reusable components, design tokens, and responsive auto-layout frames.
6. **System Usability Scale (SUS):** A standard 10-item questionnaire that measures perceived usability. A score above 68 is commonly treated as the average benchmark and is used as the project’s target.

## C3. Fit to Problem, Benefits, Risks, and Alternative
* **Fit to Problem:** Public Gold’s core friction comes from two sources: disconnected Gold Accumulation Program (GAP), Easy Payment Plan (EPP), and bullion catalog modules, and a manual bank slip upload process. A unified navigation structure and a design system address the first by shortening the path between modules and presenting them consistently. A clear payment status flow (FR6) and direct FPX/e-wallet routing (FR5) address the second by removing the upload step and showing users the outcome of their payment straight away.
* **Benefits:**
  1. Fewer steps and less confusion when moving between GAP, EPP, and bullion purchases, which is expected to reduce task completion time.
  2. Clearer feedback after payment, which is expected to improve user confidence.
  3. A consistent component library that makes future updates faster and reduces visual clutter.
  4. Less manual slip checking for administrators, if the redesigned payment flow is later implemented.
* **Limitations & Risks:**
  1. *Change Resistance:* Legacy users accustomed to old workflows may initially experience unfamiliarity with restructured navigation.
  2. *Development Overhead:* Transitioning legacy database backend flows to support automated, real-time UX components requires structural software refactoring.
* **Alternative Approach Comparison:** An alternative approach would be **Process Automation via Backend Chatbots (RAG/AI Agents)**. While a chatbot could answer questions about EPP schedules, it does not solve the fundamental visual clutter or manual payment slip upload friction. Therefore, **UX Architecture & DSS** is chosen as the primary technology because it addresses structural usability at the root level.
