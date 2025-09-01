# beanbagshotgun
Simple BeanBag Shotgun For Fivem :)


Add this into your qb-core/shared/items.lua

['weapon_beanbag'] 				= {['name'] = 'weapon_beanbag', 	 			  	       ['label'] = 'Beanbag M870', 		    ['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_BEANBAG',			           ['image'] = 'weapon_beanbagshotgun.png',  ['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A Non-Lethal Bean Bag Shotgun.'},

or Add this into your ox_inventory/data/weapons.lua

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

