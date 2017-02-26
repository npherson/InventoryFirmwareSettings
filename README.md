# Inventory Firmware Settings with ConfigMgr

This .MOF file for System Center Configuration Manager will inventory the most common/relevent firmware settings from Dell, HP, and Lenovo.

This data should help you with Windows 10 deployments so you get BIOS to UEFI, enable TPM for BitLocker, enable SecureBoot for modern security, and get Credential Guard going. Modern security requires UEFI mode and several non-default configurations...  Know what you have out there today!

Note:  Dell hardware still requires you to deploy an additional piece of software to expose the firmware settings to WMI (Dell Command | Monitor, formerly Dell OMCI). HP stopped requiring this back in about 2012. Lenovo stopped requiring it before then.  Someday, Dell... Someday!
(If you want Dell to change this, please feel free to harrass @WarrenByle, their systems management guy. He already knows/agrees, but the more customer feedback he gets, the easier it is to get the change made.)


Created by:

Nash Pherson, Microsoft MVP - Enterprise Client Management / Enterprise Mobility

nashp@nowmicro.com

@KidMystic
