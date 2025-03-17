# Incident-Handlers-Journal
<h2>Description</h2>
I worked on and completed the Google Cybersecurity Certificate in the spring of 2025. During the certification process, I completed an activity in which I reviewed the details of security incidents and documented them in an incident handler’s journal. Each entry included the timestamp of the incident, a description of the event, the tools used, the five W’s (Who, what, when, where, and why), and any additional notes on the incident. Other entries describe labs that have been completed in security tools.
<br />
<br />

<h2>File Updater Algorithm Breakdown:</h2>

<p align="center">
Assign import_file to the file name and remove_list to the IP addresses that no longer have access: <br/>
 <br />
<img src="File Updater Code 1.png" height="80%" width="80%" alt="Intilization and Reading Files"/>
<br />
<br />
Open the file and use the .read() function to convert the content into a string. Store this string in a variable called ip_addresses: <br/>
 <br />
<img src="File Updater Code 2.png" height="80%" width="80%" alt="Replacing Line in a File"/>
<br />
<br />
Use the .split() method to convert the ip_addresses string into a list: <br/>
 <br />
<img src="File Updater Code 3.png" height="80%" width="80%" alt="Finding the Word 'Total'"/>
<br />
<br />
Create a while loop that will remove an element from ip_addresses that matches an element in the remove_list. Use the .remove() method: <br/>
 <br />
<img src="File Updater Code 4.png" height="80%" width="80%" alt="Getting the Total Host Number"/>
<br />
<br />
 Use the .join() method to convert ip_addresses into a string, then use the .write() method to write over the import_file variable: <br/>
 <br />
<img src="File Updater Code 5.png" height="80%" width="80%" alt="Number of High Severity Vulnerabilities"/>
<br />
<br />


<h2>Full File Updater Code:</h2>

<p align="center">
This is the complete code for the file updater algorithm. The actual python file is attached to this repository in conjunction with this pdf version: <br/>
 <br />
<img src="PDF Logo.jpg" height="1.3%" width="1.3%" alt="PDF Logo" />
<a href="Full File Updater Code.pdf">Complete File Updater Code.pdf</a>
 <br />
 <br />
<img src="Python Logo.png" height="1.5%" width="1.5%" alt="PDF Logo" />
<a href="File_Updater.py">File_Updater.py</a>

 
</p>

</p>

<!--
