# beanbagshotgun
Simple BeanBag Shotgun For Fivem :)

This replaces the basegame shotgun w_sg_pumpshotgun, if you dont want it to replace just change the names in the correct files

I made this morely for ox_inventory, majority of it is the same when adding it into qbcore/shared/weapons/items

 Add this into your ox_inventory/data/weapons.lua

['WEAPON_BEANBAG'] = {
			label = 'Bean Bag Shotgun',
			weight = 3200,
			durability = 0.075,
			ammoname = 'ammo_beanbag',
		},

['ammo_beanbag'] = {
			label = 'Bean Bag shell(s)',
			weight = 20,
		},

Add this into ox_inventory_addons/backItems/config.lua (if you have it) 

['WEAPON_BEANBAG'] = {
        prio = 3, group = 'back', model = 'w_sg_pumpshotgun'
    },


Photos in the folder go into ox_inventory/web/images

this is my first time uploading something :)

