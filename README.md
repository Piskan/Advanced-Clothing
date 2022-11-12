<h1 align='center'>ADVANCED CLOTHING</a></h1><p align='center'><b><a href='https://discord.gg/uvRdnGPNF7'>Discord</a> - <a href='https://0resmon.tebex.io/'>Website</a></b></h5>




## USE OF EXPORT


<code>TriggerServerEvent('bp_clothingv2:checkcharacter')</code>

#### This export control your “character_skin” table in database.

![This is an image](https://i.hizliresim.com/lq5d7zn.PNG)

#### İf your data is empty open character create screen . İf your data is not empty load skins your ped.




------------------------------------------------------------------------------------------------------------------
### GET PLAYER CLOTHINGS

<code>local model,headBlend,headOverlay,headStructure,drawables,props,drawtextures,proptextures,haircolor =exports['bp_clothingv2']:getplayerclothing(xPlayer.identifier)
</code>

#### This event gets all the clothing information of the character


local ped = PlayerPedId()  OR  CreatePed id

<code>TriggerEvent('bp_clothingv2:pedyukle', ped,model,headBlend,headOverlay,headStructure,drawables,props,drawtextures,proptextures,haircolor)
</code>

#### EXAMPLE :

#### Information sent from server.lua


![This is an image](https://i.hizliresim.com/20k5rxq.PNG)

#### Information put to ped in client.lua

![This is an image](https://i.hizliresim.com/9vmto3t.PNG)

------------------------------------------------------------------------------------------------------------------
### SET JOB CLOTHING TO PLAYER

<code>TriggerEvent('bp_clothingv2:jobclothing', {['tshirt_1'] = 15,['tshirt_2'] = 3,['torso_2'] = 1, ['torso_1'] = 18, ['shoes_1'] = 5,['vest_1'] = 10 ,['pants_1'] = 15, ['mask_1'] = -1 , ['hats_1'] = 5, ['hats_2'] = 1})
</code>

#### You can add and remove job clothing like that . (list like : tshirt_1,tshirt_2,torso_1,torso_2,pants_1,pants_2, shoes_1, shoes_2 .. etc.)

### DELETE ALL CLOTHINGS (WARDROBE AND TATTOO)

<code>exports['bp_clothingv2']:deleteplayerclothing(xPlayer.identifier or Player.PlayerData.citizenid)
</code>

#### Deletes all player's clothes, wardrobes and tattoos


## ESX LEGACY IDENTITY SETTINGS

#### FIRST YOU NEED GO BP_CLOTHINGV2 > CONFİG.LUA  AND DO FALSE  Config.playerload = false and watch the video

[![Watch the video](https://kcdn-dfbd.kxcdn.com/wp-content/uploads/2014/02/Click-Here-to-Play-Video.jpg)](https://www.youtube.com/watch?v=WroQd6h_rT0)

## ESX MULTICHARACTER

#### ESX MULTICHARACTER 

####Support is not given because all settings are made for esx_skin. I'm just throwing a version that you can use without installing peds

### LINK : This site was built using [MULTICHARACTER](https://easyupload.io/eb4hu1).



