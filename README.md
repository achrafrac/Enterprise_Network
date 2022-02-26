<h1 align="center"> Enterprise Network</h1>
<h2 align="center"> Introduction</h2>
  An enterprise desires to manage locally a number of services depending on the departments. It establishes a network that will allow it to provide services that:<br/>

 * Deliver IP addresses to devices that connect to the network.</br>
 * Turn domain names into IP addresses (and vise-versa).<br/>
 * Share files over a TCP/IP network.<br/>
 * Allow the user to access web pages through a browser.<br/>
 * Transfer email over the network.<br/>
 * Manage directory services and authentication.<br/>
  <h2 align="center"> Description of the Project</h2>
  The task is to build a network divided into two subnets with:
* One DHCP server responsible for delivering addresses to devices
connected on both subnets.<br/>
* Managing the domain names will be handled by the DNS server.<br/>
* The FTP server is used to share files in only one subnet (users on the
other subnet is not allowed to access this service).<br/>
* An HTTP server managing two web pages. One is accessible to all
hosts, and one with restricted access (user-password).<br/>
* A server managing the email exchange in the company.<br/>
* LDAP (Lightweight Directory Access Protocol) is used for directory services and authentication.<br/>
<h3 align="center">Schema</h3>
![img2](https://github.com/achrafrac/Enterprise_Network/blob/main/img2.jpg?raw=true)
<h3 align="center">Tools</h3>
In this project we configured all tasks requested in virtual machines with Ubuntu as a Operating System.
<h3 align="center">Rapport</h3>
if you are interested in this project you can contact me for the report and also all the configuration steps with screenes explains each step.
<achraf.rachid2001@gmail.com>
