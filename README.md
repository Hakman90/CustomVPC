<h1>Custom VPC</h1>

<h2>Description</h2>
This Project shows you how to create a custom vpc, allocating ip ranges for subnets, creating private and public subnets, IGW, Nat Gateway and Route Tables
<br />

<h2>Project walk-through:</h2>

<p align="center">
Refer to your VPC plan and structure your VPC according to it: <br/>
<img src="https://i.imgur.com/XavBavC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Create VPC: <br/>
<img src="https://i.imgur.com/ovfjHJi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enable DNS Hostnames:  <br/>
<img src="https://i.imgur.com/898x6Na.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Subnets: <br/>
<img src="https://i.imgur.com/nn4JU2T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create an IGW:  <br/>
<img src="https://i.imgur.com/Uq56wrN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Attatch the IGW to your VPC:  <br/>
<img src="https://i.imgur.com/AcwDOPb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
Create Route Tables:  <br/>
<img src="https://i.imgur.com/WuUSgix.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br />
<br />
Associate Relevant Subnets:  <br/>
<img src="https://i.imgur.com/p639epz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
   <br />
<br />
Add Routes to IGW for Access to the public internet:  <br/>
<img src="https://i.imgur.com/KAykhdD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
