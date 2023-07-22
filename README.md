![AdvancedPlayFab__2_-removebg-preview](https://user-images.githubusercontent.com/125162270/231316691-fdf08a86-1339-4960-b28e-a8f5d64ba26a.png)

# Required Repositories
TextMeshPro  
[PlayFab SDK](https://github.com/PlayFab/UnitySDK)  
[Photon PUN](https://assetstore.unity.com/packages/tools/network/pun-2-free-119922)  
[Photon VR](https://github.com/fchb1239/PhotonVR)

# Documentation
Once you have set up the PlayFab SDK, go ahead and import AdvancedPlayfab.  
Once AdvancedPlayfab is imported, drag the AdvancedPlayfab prefab into the Hierarchy:  
![image](https://github.com/Japiter/AdvancedPlayfab/assets/125162270/82573f92-11fb-4d66-bca3-5a3110f8a532)  
Once that is finished, fill out the following required variables:  

Currency Code  
Catalogs (If multiple)  
Version Checker Enabled  
Game Version Title Key  
Game Version  
Ban String  
Ban Status Enabled  
Ban Reason  
Ban Time  
Naming PC  

Once that is finished, you are all set! Any items I did not mention are optional, but reccomended you fill out.

# Scripting
### Introduction
First, include the following namespaces:  
![image](https://github.com/Japiter/AdvancedPlayfab/assets/125162270/2163817a-1426-4c4f-a50e-0ce33afccee4)  
Any API of PlayFab may be used (Client/Server/Admin/Entity), just include their namespaces.  

Once that is done, add a reference to the prefab:  
![image](https://github.com/Japiter/AdvancedPlayfab/assets/125162270/322b04d0-a31e-41a0-a828-2f4d34955aa1)

### Requesting Inventory
To request for the players inventory (Check the players inventory for new/deleted items/currency), use the following line of code:  
![image](https://github.com/Japiter/AdvancedPlayfab/assets/125162270/3a811810-ab3e-4c37-8590-e69b7c1a5439)

### Starting AdvancedPlayfab
If there is ever a time where AdvancedPlayfab is not automatically starting, you may use this line of code in a script:  
![image](https://github.com/Japiter/AdvancedPlayfab/assets/125162270/b2b0e9b3-66ec-4382-9408-d8b1e3f068c8)

### Changing Username
If you have a custom Naming script, you can save the players username through this line:  
![image](https://github.com/Japiter/AdvancedPlayfab/assets/125162270/cacf26ed-5a1e-4496-84e9-5f39edfcb9fe)  
Inside the parenthesis, put the name string or variable of the Script.

# Help
If any help is needed, you may email me [here](mailto:advancedplayfab@gmail.com).  
You can also resort to unofficial communities to ask for help.
