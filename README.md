#Detect Bitcoin miners CPUMiner and CUDAMiner

Version: *1.0*
<br />
Author: *Ash Wilson* - *@ashmastaflash*

This is a simple policy for detecting the presence of two Bitcoin mining programs, CPUMiner and CUDAMiner.  The CPUMiner check demonstrates a process existence check and the CUDAMiner check looks for the existence of a binary in the filesystem. 


##List of Files
<!-- list below here all libraries, scripts, other files provided with this tool. 
Use asterisk-space at the beginning of a line to make a bullet item.  -->
* minerdetection.policy.json -- The policy file for uploading into the CloudPassage Portal
* README.md -- You're looking at it.
* LICENSE.txt




##Requirements and Dependencies
* This policy is focused on securing Linux operating systems

##Installation 
1. Download the minerdetection.policy.json file to your workstation
1. Log into https://portal.cloudpassage.com
1. Mouse over "Policies" and select "Configuration Policies"
1. Click on "Import Policy" and select the minerdetection.policy.json file you downloaded in step 1.

##Usage
###*Assign the policy to your server groups:*
1. Select Servers
1. For each Server Group you wish to apply this policy to, select "Edit Details" and select this policy under "Configuration"
1. The configuration check will automatically run for all hosts within the Server Groups you have the policy assigned to at the regular interval.
