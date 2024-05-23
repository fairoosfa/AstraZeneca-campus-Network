# Project Title: <b> Secure for a Campus Network </B>

ABC Campus is an education institute with 2 campuses and the main campus in Colombo. The Web server, Moodle server and the Mail servers are located at the main campus which uses high speed Internet leased line connection from the ISP. The Moodle Server which is used to do practical can only be accessed from the local network at the main campus. The main campus network connectivity is provided via wired connections. Layer 2 and Layers 3 security should be implemented on the main branch. Wireless connectivity is provided for the students only for Internet access and strict control of data usage and URL filtering is required.

The management of the institute is planning to extend the facilities available in the main campus network to the students in remote campuses through a VPN connectivity and also to minimize the possibility of cyber-attacks to the main campus network to comply with the current network security standards.
<h2> Following requirements are given by the Management. </h2>
<br> 💥	Main campus LAN need to be a Gigabit Ethernet and all Network devices need to be compatible with each other for maximum performance. </br>
<br> 💥	All the network devices should be manageable and only secure logins need be allowed on all devices.</br>
<br> 💥	AAA should use for Network Device login Authentication where possible and Syslog Server should use for record logging events, while having NTP server for time.</br>
<br> 💥	All publicly available resources including public web servers need to be separated from the main network and should move to a separate subnet. Only Secure Web Access should be enabled for web servers.</br>
<br> 💥	Network design should follow the Hierarchical Network Design Model. </br>
<br> 💥	End user authentication and managing of security polices need to centralized.</br> 
<br> 💥	Internet usage management and URL filtering need to be enforced.</br>
<br> 💥	Communication between the Head office and the Branch offices need to be highly secured.</br>
<br> 💥	Quality of service (QoS) should be implemented where possible.</br>


<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <h3>Campus Network IP Table </h3>
    
</head>
<body>

<table>
    <tr>
        <th>Department</th>
        <th>VLAN</th>
        <th>Host</th>
        <th>NetID</th>
        <th>1st IP</th>
        <th>Last IP</th>
        <th>Broadcast IP</th>
        <th>Subnet Mask</th>
    </tr>
    <tr>
        <td>Developers</td>
        <td>10</td>
        <td>22</td>
        <td>172.30.0.0</td>
        <td>172.30.0.1</td>
        <td>172.30.0.30</td>
        <td>172.30.0.31</td>
        <td>255.255.255.224</td>
    </tr>
    <tr>
        <td>Smart Lecture Hall</td>
        <td>20</td>
        <td>20</td>
        <td>172.30.0.32</td>
        <td>172.30.0.33</td>
        <td>172.30.0.62</td>
        <td>172.30.0.63</td>
        <td>255.255.255.224</td>
    </tr>
    <tr>
        <td>Lap- 01</td>
        <td>30</td>
        <td>12</td>
        <td>172.30.0.64</td>
        <td>172.30.0.65</td>
        <td>172.30.0.78</td>
        <td>172.30.0.79</td>
        <td>255.255.255.240</td>
    </tr>
    <tr>
        <td>Lap -02</td>
        <td>40</td>
        <td>12</td>
        <td>172.30.0.80</td>
        <td>172.30.0.81</td>
        <td>172.30.0.94</td>
        <td>172.30.0.95</td>
        <td>255.255.255.240</td>
    </tr>
    <tr>
        <td>Lecture Hall -01</td>
        <td>50</td>
        <td>12</td>
        <td>172.30.0.96</td>
        <td>172.30.0.97</td>
        <td>172.30.0.110</td>
        <td>172.30.0.111</td>
        <td>255.255.255.240</td>
    </tr>
    <tr>
        <td>Sales& Marketing</td>
        <td>60</td>
        <td>12</td>
        <td>172.30.0.112</td>
        <td>172.30.0.113</td>
        <td>172.30.0.126</td>
        <td>172.30.0.127</td>
        <td>255.255.255.240</td>
    </tr>
    <tr>
        <td>Network Team</td>
        <td>70</td>
        <td>10</td>
        <td>172.30.0.128</td>
        <td>172.30.0.129</td>
        <td>172.30.0.142</td>
        <td>172.30.0.143</td>
        <td>255.255.255.240</td>
    </tr>
     <tr>
        <td>Finance</td>
        <td>80</td>
        <td>4</td>
        <td>172.30.0.144</td>
        <td>172.30.0.145</td>
        <td>172.30.0.150</td>
        <td>172.30.0.151</td>
        <td>255.255.255.248</td>
    </tr>
     <tr>
        <td>Manager</td>
        <td>90</td>
        <td>1</td>
        <td>172.30.0.152</td>
        <td>172.30.0.153</td>
        <td>172.30.0.154</td>
        <td>1792.30.0.155</td>
        <td>255.255.255.252</td>
    </tr>
</table>

</body>
</html>

<br> <b> <font color="red"> This is My System Preview </font> </b> </br>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>
      <img src="https://github.com/fairoosfa/Batsol-Network-Final-Project/assets/133477567/6446a34b-7c86-4e2f-8a8c-de1c14acce37) alt="Description of the image" width="800" height="350">
  
<br> </br>
  You can see my final project & Final cisco sourse file you can check the Google Drive link in below 👇
  <br> Cisco Sourse File: <a href="https://drive.google.com/file/d/1HaqvnBUCQFHHt9EZAlGtobcC4QmmLrLW/view?usp=sharing"> Download Here</a> 

   




