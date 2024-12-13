# **osTicket Workflow: Ticket Creation and Resolution**

## **Overview**
This lab focuses on creating, managing, and resolving tickets in osTicket as end-users and help desk agents. It also includes practical insights into ticketing systems and real-world applications.

---

## **Steps Performed**

### **1. Modify Departments**
- **Changed SysAdmins Department**: Set as a Top-Level Department.
  ![7](https://github.com/user-attachments/assets/189323b8-be84-45f4-8aba-1d782d8bef53)
    
- **Deleted Maintenance Department**: Removed instead of archiving.  
  ![4](https://github.com/user-attachments/assets/d55f2f53-1fd1-4f7f-af2d-51de789a7a02)
---

### **2. Created Ticket: Mobile/Online Banking System is Down**
- **As End-User**: 
  - Created a ticket with the issue: *"Entire mobile/online banking system is down."*  
  ![11](https://github.com/user-attachments/assets/d3de8473-48b9-4ff7-9b4c-620c28b1e849)

- **As Help Desk Agent (john)**:
  - Observed ticket properties:
    - Priority: Default
    - Department: Default
    - SLA: Default
    - Assigned To: Unassigned  
  ![14](https://github.com/user-attachments/assets/cefefd37-3923-4896-9cbe-4ebd214f7b87)

- **Update Ticket Properties**: 
  - **SLA**: Sev-A (1 hour, 24/7)  
  - **Department**: Online Banking  
  ![18](https://github.com/user-attachments/assets/544e0f4b-c81a-49af-96f6-5f600494a3db)

- **Work to Completion as jane**:  
  ![24](https://github.com/user-attachments/assets/ceb71e97-7760-4a5b-863e-56167583ce51)
  ![25](https://github.com/user-attachments/assets/2f1b423b-695e-455c-b55a-f1cddb41afdb)
  ![26](https://github.com/user-attachments/assets/03971f5a-ced9-4a33-be5b-08bfb15263b5)
  ![28](https://github.com/user-attachments/assets/d09e937e-aeb6-4c12-8721-0c19dbeb617c)
---

### **3. Created Ticket: Adobe Upgrade Needed in Accounting**
- **As End-User**: 
  - Created a ticket with the issue: *"Accounting department needs Adobe upgrade, broken."*  
  ![30](https://github.com/user-attachments/assets/b3ce522b-099d-43fc-b9a1-489f8ebc5327)

- **As Help Desk Agent (john)**:
  - Observed ticket properties:
    - Priority: Default
    - Department: Default
    - SLA: Default
    - Assigned To: Unassigned  
  ![33](https://github.com/user-attachments/assets/70435f0d-3731-44f7-b9cd-87ad53992afd)

- **Updated Ticket Properties**: 
  - **SLA**: Sev-B (4 hours, 24/7)  
  - **Department**: Support  
  ![34](https://github.com/user-attachments/assets/1bb586ce-78c2-489d-bd3c-0da2efecf96d)

- **Worked to Completion as john**:  
  ![36](https://github.com/user-attachments/assets/30e52f22-cd2b-49b5-92b5-2b222dec2642)
  ![37](https://github.com/user-attachments/assets/00f70867-cb38-477f-98ad-fbde9ada2324)
  ![38](https://github.com/user-attachments/assets/d46c6fc1-3c3b-43b7-91a9-28292765e010)
  ![40](https://github.com/user-attachments/assets/7c3b6f3f-104c-4e05-96e8-74a754920340)

---

### **4. Created Ticket: CFO’s Laptop Won’t Turn On**
- **As End-User**: 
  - Created a ticket with the issue: *"CFO’s laptop will no longer turn on."*  
  ![42](https://github.com/user-attachments/assets/eba96076-60d0-4383-9161-aa1f7886c83d)

- **As Help Desk Agent (john)**:
  - Observed ticket properties:
    - Priority: Default
    - Department: Default
    - SLA: Default
    - Assigned To: Unassigned  
  ![44](https://github.com/user-attachments/assets/377a4efa-eb5e-48d1-9519-8699dacbb775)

- **Updated Ticket Properties**: 
  - **SLA**: Sev-B (4 hours, 24/7)  
  - **Department**: Support  
  ![45](https://github.com/user-attachments/assets/d7fb96f8-bfab-45cc-a372-f3149f140ed2)
  ![47](https://github.com/user-attachments/assets/dc216c48-239c-4109-828c-e1447257565f)

- **Worked to Completion as john**:  
  ![49](https://github.com/user-attachments/assets/9eac617e-01be-41e8-b9ee-21e1d3ccddf3)
  ![50](https://github.com/user-attachments/assets/5c476c4e-95d3-41ca-a11c-7706b8aa21e2)
  ![52](https://github.com/user-attachments/assets/ea0d5e94-fef8-40a5-aabf-3c980f58421f)

---

## **Real-World Ticketing System Insights**
1. **Email Notifications**: 
   - Each ticket update triggers an email notification to the user.  

2. **Ticket Intake Methods**: 
   - Tickets may originate via:
     - Phone calls
     - Chat apps
     - Emails
     - Web forms
     - Informal in-person requests  
   - Emphasize documenting all tasks by creating tickets for metrics and accountability.  
    
3. **Metrics Matter**:
   - Creating tickets for all issues ensures accurate tracking and reporting.
---

## **Conclusion**

This lab demonstrated the practical use of osTicket for ticket creation, management, and resolution. By simulating both end-user and help desk agent roles, I learned how to:

- Handle tickets efficiently through department and SLA assignment.
- Manage restricted access for escalated tickets using the admin panel.
- Work collaboratively within teams to resolve issues based on priority and scope.

Maintaining detailed ticket logs and utilizing system features like email notifications ensure accountability and improve customer satisfaction. Whether resolving technical outages or handling routine support requests, these skills form the backbone of IT service management.

