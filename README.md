
# Reeveli's Teleportation System

Custom teleportation system for Arma 3. Demo mission is included in the repository.


## Authors

- [@Reeveli](https://github.com/Reeveli)


## Addons

- [CBA](https://github.com/CBATeam/CBA_A3) (required)
- [ZEN](https://github.com/zen-mod/ZEN) (optional)
## Instructions


Custom settings can be adjusted from Addon options >> Reeveli's teleportation system.
See the attached example mission for pratical demonstration.

Teleportation point can be added via two ways:

- In the mission editor / scripting via using `Rev_tp_fnc_addPoint` -function
	Example: `[this,"My example teleportation point",west] call Rev_tp_fnc_addPoint`
Placing the code above in an object's init field will create a taleportation point tied to it. The passed parameters are the object in question, display name for the teleport menu and for which side the point is being added to.

  
  

- New teleportation point can be added by Curators while the game is on going using the cutoms module Reeveli's Teleportation system >> Add teleport point. Zeus Enchnaced mod is required for this functionality.

  
The other custom Zeus module allows curator to check currently active teleportation FOR HIS SIDE.

The teleportation point will be removed from an object if it is killed or deleted. Custom settings can be adjusted from Addon options >> Reeveli's teleportation system. See the attached example mission for pratical demonstration.

## License
Scripts included in this repository are under [APL-SA](https://www.bohemia.net/community/licenses/arma-public-license-share-alike) license.
