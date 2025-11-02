
#  Performance Testing – Laptop Request Catalog Item

This folder contains the **performance and functionality testing** documents for the NM Project **“Laptop Request Catalog Item”** developed in **ServiceNow**.

---

##  Purpose
To verify that all components of the **Laptop Request Catalog Item** (variables, UI policies, UI actions, and update set migration) function correctly across instances.

---

##  Tests Conducted
1. **Catalog Item Functionality Test**  
   - Verified creation of the *Laptop Request* item under the *Hardware* category.  
   - Checked dynamic fields and conditional visibility.  

2. **UI Policy Test**  
   - Confirmed that the *Accessories Details* field becomes visible and mandatory only when *Additional Accessories* is checked.  

3. **UI Action Test**  
   - Validated the *Reset Form* button executes the JavaScript:
     ```js
     g_form.clearForm();
     alert("The form has been reset.");
     ```
   - Ensured the form clears all input fields successfully.  

4. **Update Set Migration Test**  
   - Exported and imported the update set between ServiceNow instances.  
   - Verified that all configurations were successfully retrieved and committed.

---

##  Screenshots Included
- Creation of **Update Set**  
- Creation of **Laptop Request Catalog Item**  
- Configuration of **Variables and UI Policy**  
- **UI Action Script** setup  
- **Export & Retrieve Update Set** process  
- **Testing the catalog item** before and after selecting “Additional Accessories”  
- **Successful form reset alert**  

---

##  Results
- All configurations worked as expected.  
- The form dynamically displayed the correct fields.  
- Reset button cleared inputs successfully.  
- Update set migration worked across instances.  

---

##  Conclusion
The **Laptop Request Catalog Item** performs efficiently with no functional issues.  
Testing confirms that automation, UI behavior, and migration processes meet the expected requirements, providing a smooth and reliable ServiceNow experience.

