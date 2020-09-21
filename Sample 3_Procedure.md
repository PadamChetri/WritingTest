<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sample 3_Procedure</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__left">
    <div class="stackedit__toc">
      
<ul>
<li><a href="#backup-and-restore-operations-in-coolsoft">Backup and Restore Operations in CoolSoft</a>
<ul>
<li><a href="#client-backup">Client backup</a>
<ul>
<li></li>
</ul>
</li>
<li><a href="#restore-data-from-a-backup">Restore data from a backup</a>
<ul>
<li></li>
</ul>
</li>
</ul>
</li>
</ul>

    </div>
  </div>
  <div class="stackedit__right">
    <div class="stackedit__html">
      <p>Writing Sample_How to perform Backup and Restore in CoolSoft</p>
<h1 id="backup-and-restore-operations-in-coolsoft">Backup and Restore Operations in CoolSoft</h1>
<h2 id="client-backup">Client backup</h2>
<h4 id="about-this-task">About this task</h4>
<p>An on-demand backup is a one-time backup of data on an CoolSoft client computer. You may want to perform an on-demand backup for the first backup of the client immediately after you install the CoolSoft client software. Perform an on-demand backup before system maintenance, software installations, or software upgrades.</p>
<p><em><strong>Note</strong></em>: <em>When the CoolSoft server is using Data Domain for back-end storage, on-demand backups are written to the Data Domain by default.</em></p>
<h4 id="prerequisites">Prerequisites</h4>
<p>To perform a client backup, ensure that</p>
<ul>
<li>You have the system admin access</li>
<li>The client system status is active</li>
</ul>
<h4 id="steps">Steps</h4>
<ol>
<li>Log in to CoolSoft as system admin.<br>
The CoolSoft application dashboard is displayed.</li>
<li>In the domain tree, select the domain for the client.</li>
<li>In the list of clients, select the client computer to back up.<br>
You can only view clients in the domain for the login account. To view all clients, log in to the root domain.</li>
<li>Click <strong>BACKUP</strong>.<br>
The Backup wizard is displayed. In the Plugin pane, a list of plug-ins on the client is displayed.</li>
<li>In the Plugins pane, select the plug-in and then browse to and select the check box next to the data that you want to back up.</li>
<li>Click <strong>NEXT</strong>.<br>
The Basic Configuration window is displayed.</li>
<li>Select the backup retention policy settings:</li>
</ol>
<ul>
<li>To automatically delete this backup from the CoolSoft server after a specific amount of time, select Retention period. Specify the number of days, weeks, months, or years for the retention period.</li>
<li>To automatically delete this backup from the CoolSoft server on a specific calendar date, select End date and browse to that date on the calendar.</li>
<li>To keep this backup for as long as this client remains active in the CoolSoft  server, select No end date.</li>
</ul>
<ol start="8">
<li>From the <em><strong>Optionally select a proxy to perform backup</strong></em> list, select the proxy.<br>
The default setting is Automatic, which enables the CoolSoft server to choose the best proxy for this operation.</li>
<li>Set the plug-in options.<br>
The User Guide for each plug-in provides details on each of the options.</li>
<li>Click <strong>FINISH</strong>.</li>
</ol>
<h2 id="restore-data-from-a-backup">Restore data from a backup</h2>
<p><em><strong>Note</strong></em>: <em>You can find a backup to restore by the date of the backup. When you perform the restore, you can restore to either the original location, a different location, or multiple locations.</em></p>
<h4 id="about-this-task-1">About this task</h4>
<p>Locate backups by date when one or more of the following situations apply:</p>
<ul>
<li>You have saved all data for the client in a single backup set.</li>
<li>The exact pathname or name of the data to restore is unknown.</li>
<li>The backup that you want to restore is before a specific date or event.</li>
</ul>
<h4 id="steps-1">Steps</h4>
<ol>
<li>In the CoolSoft dashboard navigation pane, click <strong>Asset Management</strong>.<br>
The Asset Management window is displayed.</li>
<li>In the domain tree, select the domain for the client.<br>
You cannot view clients outside the domain for the login account. To view all clients, log in to the root domain.<br>
A list of CoolSoft clients is displayed in the pane below the domains list.</li>
<li>From the list of clients, select the client computer to recover.</li>
<li>(Optional) To locate backups by date:<br>
a. In the right pane, click <strong>VIEW MORE</strong>.<br>
b. Click the <strong>Backup</strong> tab.<br>
c. Click <strong>SEARCH</strong>.<br>
d. Click in the Date Range field to open the calendar view.<br>
e. From the calendar view, select a specific day or date range.<br>
e. Click <strong>RETRIEVE</strong>.<br>
f. In the list of backups, select a backup.<br>
A list of backups for the specified range appears.</li>
<li>Click the <strong>Restore</strong> tab.<br>
The Restore wizard is displayed with the Destination Client pane is displayed on the right.</li>
<li>In the Destination Client pane, perform the following steps:<br>
a. Select <strong>Restore to original client</strong>.<br>
b. Click <strong>NEXT</strong>.<br>
The Backup Content pane is displayed.</li>
<li>In the <strong>Backup Content</strong> pane, perform the following steps:<br>
a. In the left pane, select the SQL instance from the tree.<br>
The Backup Content pane displays a list of databases within the backup.<br>
b. Select the databases that you want to restore.<br>
c. Click <strong>NEXT</strong>.<br>
The Destination Location pane is displayed.</li>
<li>In the Destination Location pane, perform the following steps:<br>
a. Select Restore to the original location.<br>
b. Click <strong>NEXT</strong>.<br>
The More Options pane is displayed.</li>
<li>(Optional) In the More Option pane, toggle the Show Advanced Options switch to view advanced configuration options.<br>
The user guide for each plug-in provides details on each of the options.</li>
<li>Click <strong>NEXT</strong>.<br>
The Summary page is displayed.</li>
<li>Review the provided information, and then click <strong>FINISH</strong>.</li>
</ol>

    </div>
  </div>
</body>

</html>
