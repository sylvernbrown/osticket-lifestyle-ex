
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution (3/3)</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Example Scenarios</h2>

- Online Banking Outage
- Adobe Software Update 
- CFO's Laptop

<h2>Lifecycle Examples</h2>

<p>
1) <strong>First Example</strong>: Navigate to the osTicket <strong>User Panel</strong>.  Here, you can create a ticket from the user's perspective, in this example the issue will be related to the <strong>Online Banking</strong> department.<br />
  <br />
<img src="https://i.imgur.com/R5uGW9f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<br />
<br />

<p>
2) Create a new ticket with a summary stating <strong>"online banking is down"</strong> .<br />
  <br />
<img src="https://i.imgur.com/eFEi8Ij.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
  <Strong><i>Note: If your user isn't allowed to create a ticket, navigate to Agent Panel > Users > User Directory > [select user] > Register. You will be prompted to create a new username & password for this user.</i></Strong>
</p>
<br />
<br />
<br />
</p>

<p>
3) Proceed to the <strong>Staff Control Panel</strong> under the username of one of your helpdesk agents.  In this example, we will begin working the ticket as <strong>John.</strong><br />
  <br />
<img src="https://i.imgur.com/LFKAISw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
</p>
<br />
<br />
<br />

<p>
4) When opening a ticket in osTicket, the following settings should display.<br />
  <br />
<img src="https://i.imgur.com/GGjrkbY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
  <strong><i>Note: This panel is where classifying the ticket becomes important. Be sure to set the SLA Plan, priority, and modify the help topic if needed.  </i></strong>
</p>
<br />
<br />
<br />

<p>
5) Click on <strong>"Assign To"</strong> to re-assign a ticket to a more relevant department/team.  In this case, the team <strong>Online Banking</strong> seems to be the most fitting group to assign this ticket to.<br />
  <br />
<img src="https://i.imgur.com/ynRt2Qv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
</p>
<br />
<br />
<br />

<p>
6) Next, we assigned a <strong>SLA Plan</strong> to the ticket. Since it's classified as a critical outage and further communication with the user confirms this to be the case, we can confidently label it as <strong>Sev-A</strong>.<br />
  <br />
<img src="https://i.imgur.com/Q7sICQJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
  <strong><i>Note: While working through ticket examples, tickets will have descending priority. Sev A > Sev B > Sev C.</i></strong>
</p>
<br />
<br />
<br />

<p>
7) In the <strong>Post Reply</strong> & <strong>Post Internal Note</strong> sections in the <strong>Ticket Thread</strong>, osTicket gives you the ability to separate user communication (reply) vs internal replies.  In this example, the support team (John) is communicating to the end-user (Ken) to update him on the status of the ticket and the issue associated with it.  This practice is especially useful for department-wide or company-wide outages to keep users informed on systems availability.<br />
  <br />
<img src="https://i.imgur.com/RK5qcPA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
</p>
<br />
<br />
<br />

<p>
8) Next, John assigns this ticket to the <strong>Online Banking</strong> department since this is an <strong>Online Banking</strong> issue, the rest of this ticket will be worked on by Jane since she's part of the banking team.<br />
  <br />
<img src="https://i.imgur.com/VsLDM7T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
</p>
<br />
<br />
<br />

<p>
9) Log into <strong>Jane</strong> in the agent panel and open the ticket, click "Assigned To" and assign the ticket to <strong>Jane Doe</strong> specifically.  It's important, if part of a team like <strong>Online Banking</strong>, to claim a ticket you're working on so the rest of your team doesn't try to resolve it and can focus on other issues. <br />
  <br />
<img src="https://i.imgur.com/iJd4XRj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<img src="https://i.imgur.com/igMqA84.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
</p>
<br />
<br />
<br />

<p>
10) Since Jane now is assigned the ticket, she can make modifications, notes, edit the ticket status, update the severity, etc.<br />
  <br />
<img src="https://i.imgur.com/hn5Ljw5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
  <Strong><i>Note: She still has this ability even if she wasn't personally assigned the ticket, as she is a part of the online banking team.</i></Strong>
</p>
<br />
</p>
<br />
<br />
<br />

<p>
11) Additionally, Jane can now see the history of the ticket, update internal/external notes and close/resolve the ticket.  In this example, Jane does well to keep her team up to par on issues developing with the <strong>online banking</strong> outage.  She also communicates with the customer in this example, ensuring proper communications between support and the end-user.<br />
  <br />
<img src="https://i.imgur.com/2phUf0T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<strong><i>Note: In this example the Online Banking system was down due to an issue with a recent update, in the ticket panel Jane is able to alert relevant stakeholders and close the ticket.</i></strong>
</p>
<br />
<br />
<br />

<p>
12)<strong>Second Example:</strong> This time, the accounting department needs a simple adobe upgrade. Navigate to the <strong>Agent panel</strong> and login as <strong>John</strong> to work the ticket via the Support Desk. Begin by accessing the ticket.  <br />
  <br />
<img src="https://i.imgur.com/Rdz5uI2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
</p>
<br />
<br />
<br />

<p>
13) First, assess the appropriate <strong>SLA status</strong> of the ticket.  Since this ticket only involves one department, but still is interrupting operations at a high-level assign <strong>Sev-B</strong>.  <br />
  <br />
<img src="https://i.imgur.com/Rdz5uI2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
<strong><i>Note: It's important to remember SLA Plans are subjective and every organization has different standards in place, for demonstration purposes I am assuming the most reasonable option.</i></strong>
</p>
<br />
<br />
<br />

<p>
14) Next, since the user-reported help topic was inaccurate, i'll be changing the ticket help topic to <strong>"Other"</strong>.  The original topic was <strong>"Personal Computer Issues"</strong> but after further investigation, we found that the entire department is suffering from this issue.  <br />
  <br />
<img src="https://i.imgur.com/v5u8vqG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<strong><i>Note: It's important to communicate with the end-user to establish the accuracy of the ticket reported by the user, it's possible they don't understand the true issues they're reporting or don't understand the classification of some issues as well as support staff do.</i></strong>
</p>
<br />
<br />
<br />

<p>
15) Finally, ensure that the ticket is assigned to the user who will be working it.  In this case the ticket will be assigned to <strong>John Doe</strong> in support.  <br />
  <br />
  <br />
<img src="https://i.imgur.com/bMIjZM1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
<br />
</p>

<p>
16) In this example, Adobe required a department-wide update so the status of this development was properly communicated as seen below.  <br />
  <br />
<img src="https://i.imgur.com/7AvK8uZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
<br />
</p>


<p>
17) After fixing the issue, resolve the ticket and make a note of the issue for possible similar issues in the future.  <br />
  <br />
<img src="https://i.imgur.com/7AvK8uZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
<br />
</p>


<p>
18) <strong>Third Example:</strong> In this example, the CFO's laptop stopped working due to some physical issue with the device.  Navigate to open tickets and locate the ticket.<br />
  <br />
<img src="https://i.imgur.com/KY6mtdY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
<br />
</p>

<p>
19) Since this ticket is being worked through as <strong>John</strong>, I will self-assign the ticket to <strong>John Doe</strong>.  <br />
  <br />
<img src="https://i.imgur.com/ARpYi8n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
<br />
</p>

<p>
20) Since this is a somewhat severe scenario, due to the CFO's activites being interrupted and potential for security risks, <strong>Sev-B</strong> seems like the most appropriate SLA in this scenario.  <br />
  <br />
<img src="https://i.imgur.com/jpiYlGL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
<br />
</p>


<p>
21) This ticket is labled as High Priority because it's not a business outage, therefore it doesn't qualify as an emergency. However, since the CFO's operations are impaired, we want to resolve it as soon as we're able to.  <br />
  <br />
<img src="https://i.imgur.com/85t7pxS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
<br />
</p>

<p>
22) John found an issue with the user's battery, he communicated the issue in the <strong>Ticket Thread</strong>.  Notice that as he completed the ticket, he acknowledges his corrective action so the end-user can stay in the loop even before he is contact by support with the solution.  <br />
  <br />
<img src="https://i.imgur.com/m0cgoMK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
  <strong><i>Note: Do your best to update the ticket thread when working tickets, it's possible someone on your team may have insight about and issue if they've solved it before</strong></i>
<br />
<br />
<br />
</p>

<p>
23) John resolves the ticket, and leaves a note explaining how he fixed the issue.  <br />
  <br />
<img src="https://i.imgur.com/t9pMECb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
<br />
</p>










