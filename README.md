# 2026budget
``` markdown
# Severns Valley Baptist Church: 2026 Ministry Budget Planner

This is an interactive, single-page web application designed to help Severns Valley Baptist Church ministry staff effectively plan and develop their ministry budgets for the 2026 year. It facilitates strategic alignment of ministry activities with church-wide goals and includes robust contingency planning features.

## Features

*   **Guided Budget Planning:** A step-by-step interface guides staff through the budget creation process.
*   **Strategic Goal Alignment:** Explicitly link each budget line item to the church's 2026 strategic goals, ensuring every expenditure supports the mission.
*   **Detailed Line Item Justification:** Provide comprehensive rationale, estimated costs, and basis of calculation for each budget item.
*   **Automatic Total Calculation:** The total proposed budget updates dynamically as line items are added.
*   **Contingency Planning:** Develop proactive plans for both a 20% budget reduction and a 20% budget increase.
*   **User-Friendly Identification:** Staff enter their name (Ministry Leader) for easy identification and saving/loading of their specific budget.
*   **Cloud Data Storage (Firestore):** All budget proposals are saved securely online, allowing staff to resume their work and enabling the Pastor of Organizational Leadership to view all submitted budgets.
*   **Pastor's Overview:** A dedicated section allows the Pastor to view a list of all submitted ministry budgets and load any specific budget for detailed review.
*   **Printable Summary:** Generate a comprehensive summary of the budget proposal for review and record-keeping.
*   **Responsive Design:** Optimized for use on various devices (desktop, tablet, mobile).

## How to Use

### For Ministry Staff:

1.  **Access the Application:** Open the provided GitHub Pages URL in your web browser.
2.  **Enter Your Name:** A prompt will appear asking for your name (Ministry Leader). Enter your name to proceed. This name will be used to identify your budget.
3.  **Navigate Steps:** Use the navigation buttons (1. Goals, 2. Setup, etc.) to move through the budget planning process.
4.  **Step 2: Ministry Setup:** Fill in your Ministry Area Name, your Name (which should pre-fill from the initial prompt), and your Ministry's Mission.
5.  **Step 3: Line Items (Primary Budget Plan):**
    *   Click "+ Add New Line Item" for each expense.
    *   Fill in details like "Budget Line Reference," "Specific Item/Description," "Estimated Cost," "Quantity/Basis of Calculation," and "Rationale/Expected Impact."
    *   Crucially, select the "Primary Church Goal(s) Supported" that align with this expense.
    *   The "Total Proposed Budget" will update automatically.
6.  **Step 4: Contingency Planning:** Outline your plans for a 20% budget reduction and a 20% budget increase in the provided text areas.
7.  **Step 5: Summary:** Review your entire proposal.
8.  **Save Your Budget:** Click the "Save My Budget" button to save your progress to the cloud. You can return later and your work will be loaded automatically when you enter the same name.
9.  **Print:** Use the "Print" button to generate a physical copy of your summary.

### For the Pastor of Organizational Leadership:

1.  **Access the Application:** Open the same GitHub Pages URL.
2.  **View All Submitted Budgets:** Navigate to **Step 5: Summary**. Scroll down to the "All Submitted Budgets (Pastor's View)" section.
3.  **Load Specific Budgets:** You will see a list of all submitted budgets by ministry name and leader. Click "View Details" next to any budget to load it into the planner for review.

## Technologies Used

*   **HTML5:** Structure of the web application.
*   **Tailwind CSS:** For responsive and utility-first styling.
*   **Chart.js:** For visualizing church goals.
*   **Firebase (Firestore & Auth):** For backend data storage, saving/loading budget proposals, and anonymous user authentication.

```
