<p align="center">
<img src="https://i.imgur.com/ZOUm27S.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />
We will essentialy show here how we can work in osTicket system as a profesional helpdesk responding to tickets and resolving issues.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket (Help Desk Ticketing System)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>
<h2>Lifecycle Stages</h2>
<p align="left"> Previous Part 2 of 3: <a href="https://github.com/Afrocybersamurai/osticket-prereqs">osTicket: Post-Installation Configuration</a></p>
<br />

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p> 

<p>




<h2>Stage 1: Intake</h2>
<p> 
Go to portal, sign in and open a new ticket as a customer. For testing purposes the url is: [osTicket Link](http://localhost/osTicket/)

This stage is when a new ticket is created. 
  
Two common ways in which tickets can be submitted is through a form – such as the one shown here – or by emailing an email address that is designated for tickets. In this form, the user/customer provides their contact information, the topic/issue, and details about the issue.
</p>


<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_a237d5c3c90c4893b61f86c895b7bec4~mv2.png" height="80%" width="80%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>
<p>
Step 1: Navigate to localhost/osTicket.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_b3ba07f9729f4ef883ade027c89a4ff6~mv2.png" height="80%" width="80%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>
<p>
Step 2: Click on "Open a New Ticket."
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_eccbf785106e44e8af30930d88315cb4~mv2.png" height="60%" width="60%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>
<p>
Step 3: Fill out the contact information input fields based on the user profile created in the previous part of the lab for User 1.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_6b6896a022394f00b3bee06c9d7f4f26~mv2.png" height="60%" width="60%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>
<p>
Step 4: Select any help topic and enter an issue summary based on the scenario you want to create. Enter a brief description of the issue, then click on "Create Ticket."
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_6187920340c94e8ab47f121788a9a1d5~mv2.png" height="60%" width="60%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_52f7398a711748f9b330acb9c0e1eb8e~mv2.png" height="60%" width="60%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>
<p>
Step 5: Create two more tickets: one from User 2 and another from User 1 again.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_ad97a9a88fac4aa98c254263729b4d83~mv2.png" height="80%" width="80%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>
<p>
Step 6: Log out by going to localhost/osTicket/scp/index.php.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_30e776e008254f2385043580e8073add~mv2.png" height="80%" width="80%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>
<p>
Step 7: Log in as Agent 1, created in the previous part of the lab.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_46a88366ccb64e7dbdd3536a63c20284~mv2.png" height="80%" width="80%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>
<p>
Step 8: Select the first ticket that was created to start working it.
</p>
<br />

<h2>Stage 2: Assignment</h2>
<p> 

  Once the ticket has been submitted, the ticket can be assigned to an IT professional. in our case, to properly handled the ticket, information regarding the level of severity has been changed. The Priority was changed to “Emergency,” the SLA Plan was changed to “SEV-A,” and the Department was changed to “System Administrators.” The ticket was also assigned to “Jane Doe,” who is an administrator.
</p> 
<img src="https://i.imgur.com/Zkvxl0J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/f5rjylY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_cdf4ed8d8c79433b9b95afa33201970d~mv2.png" height="60%" width="60%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>
<p>
Step 9: Start by updating the priority level, then leave a note explaining the reason for the update.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_bf9dc6bbe4eb4143b4d867d18048e121~mv2.png" height="60%" width="60%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>
<p>
Step 10: Assign the ticket to the agent best equipped to handle it, based on their role.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_a43d998560694b30bcd8e7a151ae6581~mv2.png" height="60%" width="60%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>
<p>
Step 11: Set the service-level agreement (SLA) and make a note of the reason for the update.
</p>
<br />

<h2>Resolutions by Priority</h2>
- 1.Business Critical Outage
This priority should be set to "Emergency"

- 2. Personal Computer Issues
This priority can be "High"

- 3. Equipement Request
Normal Priority

- 4. Password Reset
Least Priority

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_63dfa80d66884b6fad45e5828ebab5fc~mv2.png" height="60%" width="60%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>
<p>
Step 12: Assign the ticket to the appropriate department and leave a note explaining the reason for the update.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_556c6729d50c4785b328fcca75d803a5~mv2.png" height="80%" width="80%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>

<h2>Stage 3: Working the Issue</h2>
<p> 
Now that the ticket has been assigned to the appropriate department and people, the IT staff can work on finding a solution to the issue. Each time a change is made to the ticket or there is an update to the situation, a comment can be made in the Ticket Thread. This allows everyone viewing the ticket to be aware of what has already done and facilitates communication between everyone involved.
</p> 
<img src="https://i.imgur.com/6bJfE6s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Step 13: Leave a reply outlining the course of action taken to solve the ticket, change the ticket status to "Resolved," and click "Post Reply."
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_d3b676c556ae402292369c1d1c92ffc8~mv2.png" height="80%" width="80%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_bb4f5b5aed2849ad896d3b18ac50e2da~mv2.png" height="80%" width="80%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_f496fe4cf86947ed9905c1ae63db1793~mv2.png" height="80%" width="80%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>
<p>
Step 14: Apply the same process to resolve subsequent support tickets, such as Ticket 2 and Ticket 3.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_d2e046dd88124f308a7deb0315ea9526~mv2.png" height="80%" width="80%" alt="osTicket: Ticket Lifecycle Examples"/>
</p>


</p>
<h2>Stage 4: Resolution</h2>
<p> 
When the issue has been resolved, the ticket can be closed. Now the ticket will move from the Open section to the Closed section. As an IT professionals, it is a good pratice to browse closed tickets since they can be a "big library"  to find solutions to open tickets.
</p> 
<img src="https://i.imgur.com/6bJfE6s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
</p>

<p>
Step 15: Provided that all the steps were executed accurately, the support ticket dashboard will be cleared of all support tickets.
</p>
<br />

<p align="center">📜 <b><i>A good example has twice the value of good advice. ~ Albert Schweitzer</b></i> 🎯</p>
