<p align="center">
    <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
    
<h1><u>osTicket - Post-Install Configuration</u></h1>
    <p>This lab demonstrates the post-install configuration of the open-source help desk ticketing system, osTicket.</p>
    <h2><em>Environments and Technologies Used</em></h2>
        <ul>
            <li>Microsoft Azure (Virtual Machines/Compute)</li>
            <li>Remote Desktop</li>
            <li>Internet Information Services (IIS)</li>
        </ul>    
    <h2><em>Operating Systems Used</em></h2>
        <ul>
            <li>Windows 10 (21H2)</li>
        </ul>
    <h2><em>Post-Install Configuration Objectives</em></h2>
        <ul>
            <li>Configuration of Roles, Departments, and Teams.</li>
            <li>Allowing anyone to create tickets.</li>
            <li>Configuration of Agents, Users, and SLA.</li>
            <li>Configuration of Help Topics.</li>
        </ul>
    <h2><u>Configuration Steps</u></h2>
        <h3> Step 1: Configuration of Roles, Departments, and Teams.</h3>
            <p>- In this first Configuration step, we go through the process of adding a new role into the osTicket system.</p>
                <img src="https://i.imgur.com/EsbVD6W.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
                <img src="https://i.imgur.com/UevStjW.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
                <img src="https://i.imgur.com/qXadZk1.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
            <p>- Once that's completed, then we went through the process of configuring Departments, and adding "Systems Administrators".</p>
                <img src="https://i.imgur.com/0i7b69Q.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
                <img src="https://i.imgur.com/Q4tmyzm.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
            <p>- From there, we went in to change the configuration of the Teams, and added Level II Support.</p>
                <img src="https://i.imgur.com/oF5IB93.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
                <img src="https://i.imgur.com/daP8wlw.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
                <img src="https://i.imgur.com/YqY8IQ4.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
            <p>- The next step that we took was to tweak the configuration so that anyone will be able to create tickets. We achieved that by going to User Settings and changed the registration required config.</p> 
                <img src="https://i.imgur.com/3DlR74p.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
            <p>- Next was to simulate adding agents (workers) and Users (customers).</p>
                <img src="https://i.imgur.com/EOzzEPk.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
                <img src="https://i.imgur.com/4jKaUIt.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
                <img src="https://i.imgur.com/2ShQMOU.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
                <img src="https://i.imgur.com/0tLaIWk.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
            <p>- Simulating the configuration of the SLA (Service Level Agreements) was next. We added 3 new SLAs.</p>
                <img src="https://i.imgur.com/Vj4ZAXB.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
                <img src="https://i.imgur.com/CV8uuxH.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
                <img src="https://i.imgur.com/acbVGvu.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
            <p>- After configuring the different SLA, lastly we changed the configuration of the Help Topics, adding a few new topics.</p>
                <img src="https://i.imgur.com/QtLqGEX.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
                <img src="https://i.imgur.com/uUljrLT.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
                <img src="https://i.imgur.com/Pt53smS.png" height="50%" width="70%" alt="Disk Sanitization Steps"/>
            <p>- This completed the post installation setup for osTicket.</p>
