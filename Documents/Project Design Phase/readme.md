#  Project Design Phase – Laptop Request Catalog Item

This folder contains the design and architecture documents for the **Laptop Request Catalog Item** NM Project developed in **ServiceNow**.

---

##  Objective
To design a structured and efficient solution that automates the manual laptop request process using **ServiceNow Service Catalog** features like dynamic variables, UI policies, and workflow automation.

---

##  Documents Included
1. **Problem–Solution Fit**  
   - Analyzes how the proposed solution addresses the current manual challenges.  
   - Identifies the alignment between user pain points and ServiceNow capabilities.

2. **Proposed Solution**  
   - Describes the technical approach:  
     - Creation of the *Laptop Request Catalog Item*  
     - Use of **UI Policies** for dynamic field visibility  
     - **UI Action** script for form reset functionality  
     - **Update Set** migration between instances  

3. **Solution Architecture**  
   - Provides a visual representation of the system flow:  
     - **User (Employee)** → Fills form in ServiceNow Portal  
     - **Service Catalog** → Handles the catalog item and variables  
     - **UI Policies & UI Actions** → Manage dynamic form behavior  
     - **Approval Workflow** → Sends requests to manager/IT  
     - **Email Notification** → Updates the user on request status  
     - **Update Set Migration** → Ensures portability between instances  

---

##  Design Summary
- The system ensures data accuracy, reduces delays, and enhances the user experience.  
- Dynamic UI and automation minimize manual intervention.  
- Architecture ensures scalability and integration with other ITSM modules.

---

## ✅ Outcome
The design phase established a **clear technical foundation** for implementation and testing, ensuring that the **Laptop Request Catalog Item** is robust, scalable, and aligned with organizational IT service needs.
