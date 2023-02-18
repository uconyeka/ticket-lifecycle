<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
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

Once a ticket is created agents working on a ticket can perform several actions based on their roles.

Agent and team assignment
A ticket can be assigned or reassigned to a team of agents or an individual agent. Department setting determines if a ticket can be assigned to agents outside the current department.

When enabled, alerts are sent out to assignee or team members.

Transferring departments
A ticket can be transferred between departments as needed.

State and status
A ticket can either be in open or closed state during it's lifecycle. Administratively-defined statuses can be used to further defined internal state of a ticket.

SLA and due dates
SLA Plans or Service Level Agreements are used to determined how long a ticket can remain open, upon creation, before it's marked overdue. System Default SLA Plan is used on new tickets, unless it's overridden at Departments, Ticket Filters and Help Topics level.

Transient SLAs are considered temporary and can be overridden by a non-transient SLA on Department transfer or Help Topic change. Setting a Due Date will override/disable any SLA set on the ticket.

Overdue tickets appear in Overdue Queue.

Ticket Editing
Ability to edit ticket information can be administratively disabled in Admin Panel for End Users or by removing the permission from Agents.
