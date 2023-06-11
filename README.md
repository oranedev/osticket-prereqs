<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://youtu.be/YpPrkijiMwk)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Azure Virtual Machine
- Database Server
- PHP & extensions
- Osticket package
- Virtual Host

<h2>Installation Steps</h2>
- Create an Azure virtual machine (VM) with the desired operating system installed.
- Choose a web server (such as Apache or Nginx) and a database server (such as MySQL or MariaDB) and install them on the VM.
- Install PHP and its extensions required by osticket, such as php-gd, php-imap, php-xml, php-mysql, and php-mbstring.
- Download the latest osticket package from the official website and extract it to the web server document root.
- Set the correct file permissions and ownership for osticket files and directories.
- Create a new MySQL/MariaDB database and user for osticket and grant the necessary privileges.
- Configure the web server to serve osticket from the document root and set up a virtual host if necessary.
- Create an inbound security rule in the Azure Network Security Group to allow inbound traffic to the web server.
- Access the osticket web installer by navigating to the osticket URL on a web browser.
- Follow the on-screen instructions to complete the osticket installation, providing the necessary database and administrative credentials when prompted.
- Test the osticket installation by logging in as an agent or a user and creating a new ticket.

<p>
<img src="https://docs.osticket.com/en/latest/_images/collabs_ticket_reply.png" height="80%" width="80%" alt="Internal Communication"/>
</p>
<p>
Using osTicket to manage internal communications in design operations. In this section, we will explore a common problem faced by businesses when using a messenger app for task management instead of leveraging dedicated ticketing systems like osTicket. We will delve into the complications arising from this approach and the benefits of shifting to a more structured and efficient solution.
</p>
<br />

<p>
<img src="https://docs.osticket.com/en/latest/_images/admin_settings_agent_agentSettings.png" height="80%" width="80%" alt="Bootstrapping task manager"/>
</p>
<p>
Introduce osTicket is a robust ticketing system designed specifically for efficient task management. Highlight its key features, such as centralized ticket creation, assignment, and tracking, customizable workflows, task prioritization, and comprehensive reporting.
</p>
<br />

<p>
<img src="https://docs.osticket.com/en/latest/_images/cccc_after_global_queue.png" height="80%" width="80%" alt="Customer Support Queue"/>
</p>
<p>
Define key performance indicators (KPIs) to assess the effectiveness of osTicket implementation. Identify metrics such as task completion rate, reduced response time, improved task visibility, and enhanced collaboration as measures of success.
</p>
<br />
