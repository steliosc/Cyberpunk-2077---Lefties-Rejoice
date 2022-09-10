# Cyberpunk 2077 - Custom Controls Guide

## User Settings

You can change all the in-game settings manually by editing the respective JSON file in your local drive.
This is handy because in some cases the game does not let you bind specific keys by default.

The file can be found in the following location (default):

```text
C:\Users\<WINDOWS_USER>\AppData\Local\CD Projekt Red\Cyberpunk 2077\UserSettings.json
```

### My Custom changes

In my case, I have to swap "A" to "Left Arrow" and "D" to "Right Arrow".

| Mapping               | Original Value | New Value     |
| --------------------- | -------------- | ------------- |
| exitVehicle           | IK_F           | IK_Enter      |
| vehicleSteerLeft      | IK_A           | IK_Left       |
| vehicleSteerRight     | IK_D           | IK_Right      |
| vehicleShootPrimary   | IK_LeftMouse   | IK_RightMouse |
| vehicleShootSecondary | IK_RightMouse  | IK_LeftMouse  |
| left                  | IK_A           | IK_Left       |
| right                 | IK_D           | IK_Right      |
| attack                | IK_LeftMouse   | IK_RightMouse |
| aim                   | IK_RightMouse  | IK_LeftMouse  |
| weapon1               | IK_1           | IK_Delete     |
| weapon2               | IK_2           | IK_End        |
| weapon3               | IK_3           | IK_PageDown   |
| weapon4               | IK_4           | IK_Home       |

---

## Input Mappings

The in-game settings' key bindings menu does not let you change all the actual controls. For example, the quick actions (e.g. pick up body) cannot be changed from there.
Or if you're a lefty (or just prefer to use the mouse with your left hand like myself), the game does not recognise the inverted mouse clicks.

To do so, you need to modify the respective XML file (game source code):

```text
C:\Program Files (x86)\Steam\steamapps\common\Cyberpunk 2077\r6\config\inputUserMappings.xml
```

(!)Please note that whenever the game is updated/patched, changes to the XML file will be reverted/purged, so you will need to change it again.

### My custom changes

I use the mouse with my left hand so I tend to assign movement to the arrow keys and bind all other keys around there (right side of the keyboard).
Since the game does not recognise my inverted mouse by default (windows settings), I have to swap all "Left Mouse" actions to "Right Mouse" and vice-versa.
Also I change all instances of the default action button "F" to "Enter".

| Mapping                                | Original Value | New Value     |
| -------------------------------------- | -------------- | ------------- |
| MouseLeft                              | IK_LeftMouse   | IK_RightMouse |
| Hit_Button                             | IK_LeftMouse   | IK_RightMouse |
| Hit2_Button                            | IK_RightMouse  | IK_LeftMouse  |
| RangedAttack_Button                    | IK_LeftMouse   | IK_RightMouse |
| RangedADS_Button                       | IK_RightMouse  | IK_LeftMouse  |
| MeleeAttack_Button                     | IK_LeftMouse   | IK_RightMouse |
| MeleeBlock_Button                      | IK_RightMouse  | IK_LeftMouse  |
| OpenQuickHackPanel_Button              | IK_F           | IK_Enter      |
| ApplyAndCloseQHackWidget               | IK_F           | IK_Enter      |
| ApplyQHack                             | IK_F           | IK_Enter      |
| InspectionZoom                         | IK_RightMouse  | IK_LeftMouse  |
| Takedown_Button                        | IK_F           | IK_Enter      |
| Vehicle_Shoot_Primary                  | IK_LeftMouse   | IK_RightMouse |
| Vehicle_Shoot_Secondary                | IK_RightMouse  | IK_LeftMouse  |
| VehicleDriverCombatRangedAttack_Button | IK_LeftMouse   | IK_RightMouse |
| ExitVehicle_Button                     | IK_F           | IK_Enter      |
| Choice1                                | IK_F           | IK_Enter      |
| Choice2                                | IK_R           | IK_Backspace  |
| ExitWheel_Button                       | IK_RightMouse  | IK_LeftMouse  |
| SelectWheelItem_Button                 | IK_LeftMouse   | IK_RightMouse |
| FreeCam_FOV_Control                    | IK_F           | IK_Enter      |
| device_click                           | IK_LeftMouse   | IK_RightMouse |
| device_click                           | IK_F           | IK_Enter      |
| vendor_checkout                        | IK_F           | IK_Enter      |
| world_map_fake_move                    | IK_LeftMouse   | IK_RightMouse |
| world_map_fake_rotate                  | IK_RightMouse  | IK_LeftMouse  |
| world_map_menu_pan_mouse               | IK_LeftMouse   | IK_RightMouse |
| world_map_menu_rotate_mouse            | IK_RightMouse  | IK_LeftMouse  |
| world_map_menu_fast_travel             | IK_LeftMouse   | IK_RightMouse |
| world_map_menu_track_waypoint          | IK_RightMouse  | IK_LeftMouse  |
| world_map_menu_open_quest              | IK_F           | IK_Enter      |
| world_map_menu_toggle_floorplan        | IK_R           | IK_Backspace  |
| click_popup                            | IK_LeftMouse   | IK_RightMouse |
| menu_click                             | IK_LeftMouse   | IK_RightMouse |
| activate                               | IK_LeftMouse   | IK_RightMouse |
| activate_secondary                     | IK_RightMouse  | IK_LeftMouse  |
| craft_item                             | IK_LeftMouse   | IK_RightMouse |
| equip_item                             | IK_LeftMouse   | IK_RightMouse |
| use_item                               | IK_LeftMouse   | IK_RightMouse |
| use_item                               | IK_F           | IK_Enter      |
| upgrade_attribute                      | IK_F           | IK_Enter      |
| upgrade_perk                           | IK_F           | IK_Enter      |
| select                                 | IK_LeftMouse   | IK_RightMouse |
| track_quest                            | IK_F           | IK_Enter      |
| PhotoMode_MouseMove                    | IK_LeftMouse   | IK_RightMouse |
| PhotoMode_MouseRotation                | IK_RightMouse  | IK_LeftMouse  |
| PhotoModeTakeScreenshot                | IK_F           | IK_Enter      |
