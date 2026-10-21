# FPIS Developer guide

## Initial setup
Install the unity sdk.
After installing the sdk create an empty gameobject and call it whatever you want.(IdManager, Game manager, etc)
Add the FPIS Id Manager script to your gameobject.
Attach a 3D TextMeshPro in the inspector.(this text will display your id)
Make sure your display text could be hidden.

## Ranks & Roles
To setup a rank/role create an empty gameobject and call it whatever your rank/role name is.
Add the FPIS Rank Manager script to your rank/role object.
In the inspector, add the user IDs of users you want to have your specific rank/role.
Attach gameobjects you want to be activated/deactivated for that rank/role in the inspector
