<h1>Dmoney API Automation Project</h1>

<h2>Project Overview</h2>
<p>
This project contains automated API testing for Dmoney system using Postman and Newman.
The flow includes user creation, activation, deposits, money transfer, and withdrawal operations.
Both positive and negative test cases are covered.
</p>

<h2>API Documentation</h2>
<p>
You can view the full API documentation here:
</p>

<a href="https://documenter.getpostman.com/view/40714220/2sBXqQGJVt" target="_blank">
Postman API Documentation
</a>

<h2>Newman Test Report</h2>
<p>
Below is the generated Newman HTML report:
</p>

<a href="http://127.0.0.1:5500/Reports/report.html" target="_blank">
View Newman Report
</a>
<img width="1116" height="953" alt="image" src="https://github.com/user-attachments/assets/4cb9eb9e-3212-44eb-a8c1-1e830dcdc768" />


<h2>🧪 Test Case Execution Report</h2>

<table border="1">
  <thead>
    <tr style="background-color: #f2f2f2;">
      <th align="left">ID</th>
      <th align="left">Test Scenario</th>
      <th align="left">Expected Result</th>
      <th align="left">Status</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>TC01</td><td>Admin Login</td><td>200 OK + Auth Token Received</td><td>✅ Passed</td></tr>
    <tr><td>TC02</td><td>User Creation (Agent/Customer)</td><td>201 Created + User Details</td><td>✅ Passed</td></tr>
    <tr><td>TC03</td><td>User Activation</td><td>200 OK + Account Activated</td><td>✅ Passed</td></tr>
    <tr><td>TC04</td><td>System to Agent Deposit</td><td>201 Created + Balance Updated</td><td>✅ Passed</td></tr>
    <tr><td>TC05</td><td>Agent Login</td><td>200 OK + Auth Token</td><td>✅ Passed</td></tr>
    <tr><td>TC06</td><td>Customer Login (1 & 2)</td><td>200 OK + Login Success</td><td>✅ Passed</td></tr>
    <tr><td>TC07</td><td>Agent to Customer Deposit</td><td>201 Created + Successful Transaction</td><td>✅ Passed</td></tr>
    <tr><td>TC08</td><td>Customer to Customer Deposit</td><td>201 Created + Transfer Success</td><td>✅ Passed</td></tr>
    <tr><td>TC09</td><td>Money Withdrawal via Agent</td><td>201 Created + Cash Out Success</td><td>✅ Passed</td></tr>
    <tr><td>TC10</td><td>Invalid Login Attempt</td><td>401 Unauthorized / 404 Not Found</td><td>✅ Passed</td></tr>
    <tr><td>TC11</td><td>Unauthorized User Creation</td><td>401 Unauthorized (No Token)</td><td>✅ Passed</td></tr>
    <tr><td>TC12</td><td>Unauthorized Deposit Attempt</td><td>401 Unauthorized</td><td>✅ Passed</td></tr>
    <tr><td>TC13</td><td>Transaction Limit Exceeded</td><td>406 Not Acceptable</td><td>✅ Passed</td></tr>
    <tr><td>TC14</td><td>Unauthorized Withdrawal</td><td>401 Unauthorized</td><td>✅ Passed</td></tr>
  </tbody>
</table>

<h2>Tools Used</h2>
<ul>
  <li>Postman</li>
  <li>Newman</li>
  <li>JavaScript (Test Scripts)</li>
  <li>HTML Report Generator (htmlextra)</li>
</ul>

<h2>Author</h2>
<p>Nishat Afla</p>
