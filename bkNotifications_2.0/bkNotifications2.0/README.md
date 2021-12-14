`bkNotificationsV2`

**EN:** Go to : `es_extended/client/functions.lua` and past this (replace existing functions):  
**ES:** Deberás ir a : `es_extended/client/functions.lua` y pegar esto (reemplazar funciones existentes):
```lua
ESX.ShowNotification = function(msg)
	TriggerEvent("esx_notifications:showNotification", {text = msg})
end
```
```lua
ESX.ShowAdvancedNotification = function(msg)
	TriggerEvent("esx_notifications:showAdvancedNotification", {text = msg})
end
```
**EN:** Hope you like it ;)  
**ES:** Espero que te guste ;)
