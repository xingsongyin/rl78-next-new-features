# rl78-next-new-features
This is a demo repo for the Smart Configurator new features(SMS/ELCL) used data content.

## Overview
SNOOZE Mode Sequencer (SMS) and Logic Event Link Controller(ELCL) are 2 new functions for Renesas RL78/G23,G24 MCU Group Product.
These 2 additional functions which is never in conventional RL78/G1x.
- SMS is total low power concept.
- ELCL is intelligent concept which support for hardware field updates of new functions.

Smart Configurator is Renesas code assitant tool to help user generate generate code and application. SC will support SMS/ELCL tool to help user to make SMS/ELCL design and generate the related codes.

SMS/ELCL tool in Smart Configurator used Data Driven Method for the tool function support.
User can easily download and update data content to uggrade tool function, user even can make his own data content according to provided data specification to extend the tool functions.
This git repo include the data contents for SMS/ELCL, all data format is XML format. Anyone(RL78 fans) can clone this repo and contribute his new date content which extend the SMS/ELCL tool function.

Download the latest SMS/ELCL data content package from the [Releases page](https://github.com/xingsongyin/rl78-next-new-features/releases).

### Supported RL78 MCU Group
- RL78/G23
- RL78/G24

### Setup Instructions
Download SMS/ECLC data file and extract & copy to specificed SC data file folder.
e2 studio: C:\Users\<name>\.eclipse\com.renesas.platform_download\RL78_Modules\SMS_Modules
stand alone SC:  C:\Users\<name>\.eclipse\com.renesas.smc.rcp.rl78.product_download\RL78_Modules\SMS_Modules

#### For new users that are using Smart Configurator for RL78/G23 with e² studio
1.	Download the data content with e² studio Installer from the Assets section of the [latest release](https://github.com/renesas/fsp/releases).
2.	Run the installer. This will install the e² studio tool, FSP packs, GCC toolchain and other tools required to use this software. No additional installations are required.

### Starting Development
1. Open e² studio and click File > New > RL78 C/C++ Project > Select RL78/G23 device and Checked Smart Configurator.

### Related Links
SMS/ELCL data Releases :  https://github.com/xingsongyin/rl78-next-new-features/releases

SMS/ELCL data content specification : https://renesas.github.io/fsp

RL78 Product Information: www.renesas.com/rl78

RL78 Product Support Forum: www.renesas.com/rl78/forum

e² studio : www.renesas.com/e2studio

Example Projects : www.renesas.com/ra/example-projects

Knowledge Base: https://en-support.renesas.com/knowledgeBase/category/31087

Support: www.renesas.com/support 
