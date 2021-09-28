# vyast-weaponDetection
A simple, lightweight FiveM resource that will stop players from using modified game files to gain an unfair combat advantage.

Specifically, this will prevent players from modifying the native ammo clip size & damage values of their weapons.

There are currently only two weapons listed in the config by default. Add as many weapons to this list as you would like to detect. 

The values inside the config need to be set to whatever values are active on your server, those being the default values from the default weapons.meta file, or if you are using a custom weapons.meta file on your server, you need to adjust the values accordingly.

By default, this resource runs 0.00ms server-sided and ranges from 0.00 - 0.01ms client sided. The client sided performance may ever so slightly decrease depending on how many more weapons you add to the config.

The two values within your weapons.meta file that correspond to the values within the config.lua are as follows:
weapons.meta: "Damage" & "ClipSize"
config.lua: "clipSize" & "damage"
