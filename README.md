# FiveM-Addon-Vehicle-Template
- create a new file called “__resource.lua”
```lua
-- TORTONIGHT
resource_manifest_version 'f15e72ec-3972-4fe4-9c7d-afc5394ae207'

files {
	      'data/carcols.meta',
	      'data/carvariations.meta',
	      'data/handling.meta',
	      'data/vehicles.meta',
        'data/dlctext.meta',
        --'data/contentunlocks.meta',
        'data/ai/vehiclelayouts.meta',
        --'data/shop_vehicle.meta',
}


data_file 'CARCOLS_FILE' 'data/carcols.meta'
data_file 'VEHICLE_VARIATION_FILE' 'data/carvariations.meta'
data_file 'HANDLING_FILE' 'data/handling.meta'
data_file 'VEHICLE_METADATA_FILE' 'data/vehicles.meta'
data_file 'DLC_TEXT_FILE' 'data/dlctext.meta'
--data_file 'CONTENT_UNLOCKING_META_FILE' 'data/contentunlocks.meta'
data_file 'VEHICLE_LAYOUTS_FILE' 'data/ai/vehiclelayouts.meta'
--data_file 'VEHICLE_SHOP_DLC_FILE' 'data/shop_vehicle.meta'


client_script { 'client/vehicle_name.lua' }
```
