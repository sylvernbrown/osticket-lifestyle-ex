
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

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
1) Navigate to the osTicket <strong>User Panel</strong>.  Here, you can create a ticket from the user's perspective, in this example the issue will be related to the <strong>Online Banking</strong> department.<br />
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
<br />
<br />
<br />

<p>
3) Proceed to the <strong>Staff Control Panel</strong> under the username of one of your helpdesk agents.  In this example, we will begin working the ticket as <strong>John.</strong><br />
  <br />
<img src="https://i.imgur.com/LFKAISw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
</p>
<br />
<br />

4) When opening a ticket in osTicket, the following settings should display.<br />
  <br />
<img src="https://i.imgur.com/GGjrkbY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
</p>
<br />
<br />

5) Click on <strong>Assign To</strong> to re-assign a ticket to a more relevant department/team.  In this case, the team <strong>Online Banking</strong> seems to be the most fitting to assign this ticket to.<br />
  <br />
<img src="https://i.imgur.com/GGjrkbY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
</p>
<br />
<br />

6) Next, we assigned a <strong>SLA Plan</strong> to the ticket, since it's classified as a critical outage and further questioning confirms this to be the case, we can confidently label it as <strong>Sev-A</strong>.<br />
  <br />
<img src="https://i.imgur.com/Q7sICQJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
</p>
<br />

7)In the <strong>Post Reply</strong> & <strong>Post Internal Note</strong> sections in the ticket notes, osTicket gives you the ability to separate user communication (reply) vs internal replies.  An example of these communications are shown below.<br />
  <br />
<img src="https://i.imgur.com/RK5qcPA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
</p>
<br />
<br />

8)Since <strong>John</strong>assigned the ticket to <strong>Online Banking</strong> the Agents on the <strong>Online Banking</strong> team should now have access to this ticket. 
 To check if this is the case, log into <strong>Jane</strong> on the Agent panel.<br />
  <br />
<img src="https://i.imgur.com/VsLDM7T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
</p>
<br />
<br />

9) Now, we are going to navigate to Jane's agent account.  In the open tickets in osTicket, since we assigned the ticked to Online Banking Jane can access it since she's a part of that team.  Open the ticket, click "Assigned To" and assign the ticket to Jane Doe. 
 To check if this is the case, log into <strong>Jane</strong> on the Agent panel.<br />
  <br />
<img src="https://i.imgur.com/iJd4XRj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<img src="https://i.imgur.com/igMqA84.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
</p>
<br />
<br />

10) Since Jane now is assigned the ticket, she can make modifications, notes, edit the ticket status, update the severity,etc.<br />
  <br />
  <br />
<img src="https://i.imgur.com/hn5Ljw5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
</p>
<br />
</p>
<br />
<br />

<p>
11) Additionally, Jane can now see the history of the ticket, update internal/external notes and close/resolve the ticket .<br />
  <br />
<img src="https://i.imgur.com/2phUf0T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<strong><i>Note: In this example the Online Banking system was down due to an issue with a recent update, in the ticket panel Jane is able to alert relevant stakeholders and close the ticket.</i></strong>
</p>
<br />
<br />

<p>
12) Now, navigate to the end-user panel and open a new ticket.  For demonstration purposes, the accounting department needs a simple adobe upgrade.<br />
  <br />
<img src="https://i.imgur.com/2phUf0T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<strong><i>Note: In this example the Online Banking system was down due to an issue with a recent update, in the ticket panel Jane is able to alert relevant stakeholders and close the ticket.</i></strong>
</p>
<br />
<br />

<p>
13) Navigate to the Agent panel and login as John to work the ticket via the Support Desk.  Begin by accessing the ticket.  <br />
  <br />
<img src="https://i.imgur.com/Rdz5uI2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
<strong><i>Note: In this example the Online Banking system was down due to an issue with a recent update, in the ticket panel Jane is able to alert relevant stakeholders and close the ticket.</i></strong>
</p>
<br />
<br />

14) First, assess the appropriate SLA status of the ticket.  Since this ticket only requires one department, but still is interrupting operations at a high-level assign Sev-B  <br />
  <br />
<img src="https://i.imgur.com/Rdz5uI2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
<strong><i>Note: In this example the Online Banking system was down due to an issue with a recent update, in the ticket panel Jane is able to alert relevant stakeholders and close the ticket.</i></strong>
</p>
<br />
<br />

15) Next, since the user-reported help topic was inaccurate, i'll be changing the ticket help topic to "other".  The original topic was "Personal Computer Issues" but after further investigation, we found that the entire department is suffering from this issue.  <br />
  <br />
<img src="https://i.imgur.com/v5u8vqG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
<strong><i>Note: In this example the Online Banking system was down due to an issue with a recent update, in the ticket panel Jane is able to alert relevant stakeholders and close the ticket.</i></strong>
</p>
<br />
<br />

16) Finally, ensure that the ticket is assigned to the user who will be working it.  In this case the ticket will be assigned to John Doe in support.  <br />
  <br />
<img src="https://i.imgur.com/bMIjZM1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
</p>
<br />
<br />

17) In this example, Adobe required a department-wide update so the status of this development was properly communicated as seen below.  <br />
  <br />
<img src="https://i.imgur.com/7AvK8uZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
</p>
<br />
<br />

18) After fixing the issue, resolve the ticket and make a note of the issue for possible similar issues in the future.  <br />
  <br />
<img src="https://i.imgur.com/7AvK8uZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
</p>
<br />
<br />

19) .  <br />
  <br />
<img src="https://i.imgur.com/KY6mtdY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
</p>
<br />
<br />

20) .  <br />
  <br />
<img src="https://i.imgur.com/ARpYi8n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
</p>
<br />
<br />

21) .  <br />
  <br />
<img src="https://i.imgur.com/jpiYlGL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
</p>
<br />
<br />

22) .  <br />
  <br />
<img src="https://i.imgur.com/85t7pxS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
</p>
<br />
<br />

23) .  <br />
  <br />
<img src="https://i.imgur.com/m0cgoMK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
</p>
<br />
<br />

24) .  <br />
  <br />
<img src="https://i.imgur.com/t9pMECb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
<br />
<br />
</p>
<br />
<br />









