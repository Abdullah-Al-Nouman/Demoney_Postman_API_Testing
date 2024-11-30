# Dmoney REST API Testing

## 📄 Project Overview
This repository contains test cases, reports, and documentation for testing the Dmoney REST API. The API enables functionalities such as creating users, depositing money, checking balances, and processing transactions between entities like Agents, Customers, and Merchants.

---

## 📝 Test Cases
Comprehensive test cases have been written for the following scenarios:

1. Admin creates an Agent, 2 random Customers, and a Merchant.
2. Deposit money from the SYSTEM account to the Agent (range: 10 TK to 10,000 TK).
3. Agent deposits money to one of the Customers.
4. Check the Agent's balance.
5. Customer sends money to another Customer.
6. Withdraw money from a Customer to the Agent (range: 10 TK to 10,000 TK).
7. Check the Customer's balance and transaction statement by `trnxId`.
8. Make a payment from the second Customer to the Merchant.
9. Check the second Customer's balance and transaction statement.
10. Check the Merchant's balance.

> 📌 **Link to Test Case Document:**  
[View Test Cases]([./path-to-your-test-cases-document](https://docs.google.com/spreadsheets/d/1hg1lb3_okQ9zDZL-hS0WJI5M96OYMne5/edit?usp=drive_link&ouid=111352479357986755938&rtpof=true&sd=true))

---

## 🐞 Bug Reports
Identified bugs during the API testing process have been documented with detailed steps to reproduce, expected vs. actual behavior, and severity.

> 📌 **Link to Bug Reports Document:**  
[View Bug Reports](https://docs.google.com/spreadsheets/d/1xJvSnm76aVPFB9VuIiZV4dz8zkhELzpI/edit?usp=drive_link&ouid=111352479357986755938&rtpof=true&sd=true)

---

## 📊 Postman Reports
The Postman HTML report provides detailed insights into the API tests, including execution status, request-response details, and assertions.

> 📌 **Link to Postman HTML Report:**  
[View Postman HTML Report](https://drive.google.com/file/d/1JpFK5w8VMG0EaZYjOCs-K9IAM6PY8feO/view?usp=drive_link)


### **Newman Report**

#### **1. Report Screenshot-01**
![image](https://github.com/user-attachments/assets/aac37b83-4a54-479a-91d1-a60c9a7a12cf)


#### **2. Report Screenshot-02**
![Report Screenshot 2](https://github.com/user-attachments/assets/a08c0584-0038-4cba-8dd0-f53743fe31be)




---



---

## 📘 API Documentation
The Postman API documentation provides a detailed overview of all endpoints, request parameters, and response formats for the Dmoney REST API.

> 📌 **Link to Postman Documentation:**  
[View API Documentation](https://documenter.getpostman.com/view/39862330/2sAYBXDBjE)

---

## ⚙️ How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/Abdullah-Al-Nouman/Demoney_Postman_API_Testing.git

