# mobile-banking-funds-transfer-api-testing-
Validate the Funds Transfer functionality of a Mobile Banking App through manual and API testing. Ensure seamless fund transfers between accounts and robust error handling.




#### **Objective:**  
Validate the Funds Transfer functionality of a Mobile Banking App through manual and API testing. Ensure seamless fund transfers between accounts and robust error handling.

#### **Features Tested:**  
- Transfer between same bank accounts.  
- Transfer to accounts in different banks (NEFT/IMPS/RTGS).  
- Validate beneficiary addition before transfer.  
- Handle daily/monthly transfer limits.  
- Real-time transaction status updates.

---

### **Tools Used:**  
- **Postman**: API testing and validation.  
- **Figma**: UI comparison for design consistency.  
- **Excel/Sheets**: Documentation of test cases, bug reports, and test data.  
- **GitHub**: Repository management.

---

### **Key Components:**  

#### **1. API Testing:**  
- **Endpoints Covered:**  
  - `/transfer/funds` (POST)  
  - `/transfer/status` (GET)  
  - `/beneficiary/add` (POST)  
- **Test Scenarios:**  
  - Successful funds transfer.  
  - Transfer with invalid account details.  
  - Transfer exceeding daily limits.  
  - Verification of transaction reference ID.  

- **Tools:** Postman (Collection and Environment setup provided).

---

#### **2. Functional Testing:**  
- Tested user journeys:
  - Add beneficiary -> Authenticate -> Transfer funds -> Confirm transaction.  
  - Test invalid data inputs and error messages.  

#### **3. Test Data:**  
- Stored in JSON and Excel formats for reusability.  
- Example Data Points:  
  - Valid and invalid account numbers.  
  - Minimum and maximum transfer amounts.

---

### **Deliverables:**  
1. Test cases for functional and API testing (Excel).  
2. Postman collection and environment files.  
3. API test execution reports (HTML).  
4. Screenshots of success and error flows.  
5. Documentation detailing the process and findings.

---


