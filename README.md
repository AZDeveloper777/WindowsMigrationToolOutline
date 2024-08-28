Goal: Develop a sustainable FOSS Windows 10/11 application that will help mostly-non-technical Windows users migrate to Linux

For the application to be sustainable, it will need revenue.  To generate that revenue, we could use sponsored links that benefit a non-profit that pays for development, support and other expenses.

Use case:  
A non-technical Windows 10/11 user desires to migrate away from Windows.  
This application would do the following:  
1. Build a data model of the users hardware and software  
2. Run analysis of that data model and make reasonable recommendations.  
3. Facilitate the implementation of those recommendations should the user choose to act.

If there are empty RAM slots or if RAM can be upgraded, generate sponsored links for the exact parts the user would need.  
If the system has unused NVMe slots, sponsored links for a good value NVMe SSD.  
If the system is on SATA spinning disks, sponsored links for SATA SSD.  
etc.

What question(s) should we ask to determine if the user should be guided towards a rolling release or a traditional release cycle ?  

Proposed Features: 
- After analysis and interactive decision tree, give links to the ISO downloads for the recommended distros.  
- If we can bundle something like Rufus, give the user a 1-click experience to burn the ISO to a USB drive.  
- Use the analysis data to create a user data backup plan  
- Use the analysis data to recommend reasonalbe FOSS replacements for their current programs. The most awesome version of this would build those FOSS replacements into the ISO for their distro.   
- Use the analysis data to generate instructions for the user to change their BIOS to boot off of the USB drive.  Have a QR code with this.  
- Possibly offer to clone the Windows install for later recovery if they change their mind. Need 2nd USB drive.  
- Not sure if this tech exists as FOSS, but offer to do physical-to-virtual machine  conversion so the user can use their Windows programs while they learn / find FOSS equivalents  

Support:  
- Use the revenue from sponsored links to provide a moderated and staffed support forum.  
  
