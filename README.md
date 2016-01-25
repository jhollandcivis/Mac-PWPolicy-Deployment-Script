# Mac-PWPolicy-Deployment-Script

Purpose:  Create a pwpolicy XML file based upon variables and options included below.
          Policy is applied and then file gets deleted. Use "sudo pwpolicy -u <user> -getaccountpolicies"
          to see it, and "sudo pwpolicy -u <user> -clearaccountpolicies" to clear it.

Usage:  Edit variables in Variable flowerbox below.
        Then run as a policy from Casper, or standalone as root.

Tested on: OS X 10.10 and 10.11

Authors: Danny Friedman, Civis Analytics IT Manager, CCA, civisanalytics.com
         Jeff Holland, Civis Analytics Sr. Security Engineer, CISSP/GCUX, civisanalytics.com

License: BSD 3-clause (see license.txt)
