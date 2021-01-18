# VM Startup guide
**Context:** 

Until now, for each POV/Pilot/Bootcamp,  we had to manually install a new instance of UP Process Mining. To remedy this,  we developed several Azure VM templates which makes this process significantly easier and quicker. 

**Detailed guide can be found here:** https://uipath-my.sharepoint.com/:w:/p/martijn_copier/ET0gURzreXhJjz0TGq0Adu4BBIRPoQRg9zcfiK_hGarBXg?e=oo8ciM


Prerequisites:
-	Azure portal account (check if you have a default UiPath account). 
-	VM Templates in JSON (currently hosted on Martijn C Github)

Steps overview:
1.	Create a Resource Group (still in debate whether this step can be automated)
2.	Add and copy VM template to Azure
3.	Set desired parameters for VM (POV/Pilot/Bootcamp)
4.	Wait for VM to start, access it though browser using Full Server name
