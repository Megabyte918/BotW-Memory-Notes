# Address notes for Breath of the Wild
#### This file contains information about certain Addresses and what they do.

## _Link's data_ (v1.2.0, USA)
|Address |  What the value is     |   Notes
|--------|------------------------|----------
|439D8738|Link's Gravity          |3F800000 = 1x Gravity (Normal)
|439D8724|Link's Speed            |3F800000 = 1x Speed (Normal)
|424527A4|Current Stamina         |Float Value
|43A77EA8|Link's Stealth          |00000000 = Completely silent

## _Link's data_ (v1.3.0, USA)
|Address |  What the value is     |   Notes
|--------|------------------------|----------
|4381010C|Link's Jump Height      |Float Value
|438100F8|Link's Gravity          |3F800000 = 1x Gravity (Normal)
|438100E4|Link's Speed            |3F800000 = 1x Speed (Normal)
|4228B0CC|Current Stamina         |Float Value
|438AF228|Link's Stealth          |Float Value, 00000000 = Completely silent
|43907954|Link's Defense          |Increases with amount of Armor

## _Weather & Skybox_ (v1.2.0, USA)
|Address |    What the value is    |   Notes
|--------|-------------------------|----------
|407CE158|Lightning strike Interval|Normal delay is about 00000080
|3FF8E72B|If Blood moon is tonight |00000000 = False, 00000001 = True
|407CDDA8|Clouds                   |00000000 = Off, 3F800000 = On
|407CDE1C|Current Weather          |*See Below

*See [here](https://github.com/Megabyte918/BotW-Cheat-Codes/blob/master/v1.2.0/Weather%20%26%20Skybox%20Modifier%20%5BSkoolzout1%5D) for more information on weather effects.

## _Weather & Skybox_ (v1.3.0, USA)
|Address |    What the value is        |   Notes
|--------|-----------------------------|----------
|406025C0|Lightning Sky Effect Duration|Decimal Value
|406025C4|Lightning Strike Buildup     |Decimal Value
|40602214|Clouds                       |00000000 = Off, 3F800000 = On
|40602288|Current Weather              |*See Below

*See [here](https://github.com/Megabyte918/BotW-Cheat-Codes/blob/master/v1.3.0/Weather%20%26%20Skybox%20Modifier%20%5BSkoolzout1%5D) for more information on weather effects.

## _Savegame data_ (v1.2.0, USA)
|Address |  What the value is       |   Notes
|--------|--------------------------|----------
|40123BA4|Current Rupees            |Decimal Value
|401242E4|Current Mon               |Decimal Value
|424527A0|Overall Heart Containers  |Float value, **4** = 1 conatiner, **120** = 30 containers
|424527A8|Overall Stamina           |Float value, regular max stamina value is 3000
|401244E0|Max Weapon Inventory Slots|Decimal Value
|401244E4|Weapon Inventory Slots    |Decimal Value
|4012A400|Max Bow Inventory Slots   |Decimal Value
|4012A404|Bow Inventory Slots       |Decimal Value
|4012A420|Max Shield Inventory Slots|Decimal Value
|4012A424|Shield Inventory Slots    |Decimal Value

## _Savegame data_ (v1.3.0, USA)
|Address |  What the value is       |   Notes
|--------|--------------------------|----------
|3FF52244|Current Rupees            |Decimal Value
|3FF52984|Current Mon               |Decimal Value
|4228B0C8|Overall Heart Containers  |Float value, **4** = 1 conatiner, **120** = 30 containers
|4228B0D0|Overall Stamina           |Float value, regular max stamina value is 3000
|3FF52B80|Max Weapon Inventory Slots|Decimal Value
|3FF52B84|Weapon Inventory Slots    |Decimal Value
|3FF58AA0|Max Bow Inventory Slots   |Decimal Value
|3FF58AA4|Bow Inventory Slots       |Decimal Value
|3FF58AC0|Max Sheild Inventory Slots|Decimal Value
|3FF58AC4|Sheild Inventory Slots    |Decimal Value

## _Visual Effects_ (v1.3.0, USA)
|Address |  What the value is    |   Notes
|--------|-----------------------|------------
|405FC458|Red-ness of the game   |Float Value
|405FC45C|Green-ness of the game |Float Value
|405FC460|Blue-ness of the game  |Float Value
|405FC458|Red Haze value         |Float Value
|405FC45C|Green Haze value       |Float Value
|405FC460|Blue Haze value        |Float Value
|405FC474|Sky brightness         |Float Value
|405FC494|Brightness of the sun  |Float Value
|405FC4D4|Fog amount?            |Float Value
|406458D4|Glow amount/brightness?|Float Value
|40645898|General brightness?    |Float Value
|40645078|Red-ness of the Sky    |Float Value
|4064507C|Green-ness of the Sky  |Float Value
|40645080|Blue-ness of the Sky   |Float Value
|40645094|Sky brightness 2       |Float Value

## _Visual Effects_ (v1.1.1, USA)
|Address |  What the value is            |   Notes
|--------|-------------------------------|------------
|407F5988|Red-ness of the game           |Float Value
|407F598C|Green-ness of the game         |Float Value
|407F5990|Blue-ness of the game          |Float Value
|407F59A4|Red Haze-ish value             |Float Value
|407F59A8|Green Haze value               |Float Value
|407F59AC|Blue Haze value                |Float Value
|407C1AC8|Red air thing?                 |Float Value
|407C1728|Green fog                      |Float Value
|407C179C|Red fog                        |Float Value
|407C1818|Blue fog                       |Float Value
|407C090C|All colours Glow Radius        |Float Value
|407C0908|Blue Glow Radius               |Float Value
|407C0904|Green Glow Radius              |Float Value
|407C0900|Red Glow Radius                |Float Value
|407C0970|All Glow Brightness            |Float Value
|407C0968|Green Glow Brightness          |Float Value
|407C096C|Blue Glow Brightness           |Float Value
|407C0964|Red Glow Brightness            |Float Value
|407F61C4|Overall In game Brightness     |Float Value
|408D4008|Icons stretch amount upright   |Float Value
|408D4014|Icons stretch amount down-left |Float Value
|408D4018|Icons stretch amount down-right|Float Value
|408D401C|Icon Skew?                     |Float Value
|407B5C70|The suns distance away from you|Float Value

## _Link's Model_ (v1.3.0, USA)
|Address |  What the value is   |   Notes
|--------|----------------------|------------
|43809030|Right Leg Size       |Float Value, Order: XZY
|43908ED8|Right Leg Position   |Float Value, Order: YX
|43816204|Wallet Size          |Float Value, Order: YXZ
|43905148|Head Facing Direction|Float Value, Normal = 3F800000?
|439050C8|Head Size            |Float Value, Order: XZY
|439051F8|Neck Size            |Float Value, Order: XZY
|43806E64|Visibility           |Float Value, Normal = 3F800000
|43806E68|Visibility 2         |Float Value, Normal = 3F800000
|43806E6C|Visibility 3         |Float Value, Normal = 3F800000
|43806DA4|Overall Size         |Float Value, Order: YXZ
|43814484|Overall Size 2       |Float Value, Order: YXZ
|43811F80|Upper Body Size      |Float Value, Order: YXZ
|43905328|Stomach Size         |Float Value, Order: XZY

## _Link's Model_ (v1.0.0, USA)
|Address |  What the value is       |   Notes
|--------|--------------------------|------------
|436C9B20|Head Facing Direction     |Float Value, Normal = 3F800000?
|436C9B34|Head Size                 |Float Value, Order: YXZ
|436C9B04|Neck Size                 |Float Value, Order: XZY
|4369B8EC|Distance from Ground      |Float Value, Normal = 00000000
|4369B8FC|Visibility                |Float Value, Normal = 3F800000
|4369B8C8|Overall Size              |Float Value, Order: YXZ
|436C91A0|Upper Body Size           |Float Value, Order: YXZ
|436C91DC|Shoulder Size             |Float Value, Order: YXZ
|436C9324|Left Hand Size            |Float Value, Normal = 3F800000
|436C93E4|Left Hand Size 2          |Float Value, Normal = 3F800000
|436C9414|Left Hand Size 3          |Float Value, Normal = 3F800000
|436C9684|Right Arm Size            |Float Value, Normal = 3F800000
|436C96B4|Right Arm Size 2          |Float Value, Normal = 3F800000
|436C9714|Right Arm Size 3          |Float Value, Normal = 3F800000
|436C9204|Left Arm Size             |Float Value, Normal = 3F800000
|436C9234|Left Arm Size 2           |Float Value, Normal = 3F800000
|436C9294|Left Arm Size 3           |Float Value, Normal = 3F800000
|436C77B4|Hip Size                  |Float Value, Order: YXZ
|436C77C0|Lower Body Coordinates    |Float Value, Order: ???
|4369B8FC|Hitbox distance from Model|Float Value, Normal = 00000000

## _Miscellaneous_ (v1.3.0, USA)
|Address |  What the value is     |   Notes
|--------|------------------------|------------
|405FFFF0|Current Time            |*See Below
|405FFFF8|Current Time 2          |*See Below
|405FFFFC|Speed of Time           |Float Value, 3C088889 = Normal

See [here](https://github.com/Megabyte918/BotW-Cheat-Codes/blob/master/v1.3.0/Freeze%20a%20Specific%20Time%20%5BSkoolzout1%5D) for more information on time.

## _Miscellaneous_ (v1.0.0, USA)
|Address |  What the value is     |   Notes
|--------|------------------------|------------
|4369B8F4|Gravity                 |Normal = 3F800000
|1074695C|Nearby Object Visibility|Float Value
|430B0B28|Ground Visibility State |Normal = 3F800000
