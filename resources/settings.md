# Some useful settings for Swedish vector charts

## Template

There is a template included in "resources/". To use it, copy the file "resources/OCPNTemplate-6cd87037-2b2f-4c50-9750-776764636100.conf" to your "config" directory and edit the "configs.xml" and paste the **contents** of the file "resources/template.xml" in between the `<configs> <configs/>` tags.

(Re-)Start OpenCPN and go to Options -> Display -> Templates. The added template "Swedish Charts" should be in the list. The setting below (except the fonts) should be in the template.

## User standard objects

In OpenCPN it is, for some objects/symbols, possible to choose if they should be visible or not.
Have a look in Options -> Charts -> Vector Chart Display -> User Standard Objects.

Many of the objects in this list seem to have no effect in Swedish vector charts. Below are some of the objects that do have an impact and examples of how they appear in the charts.

| Setting                             | On                                                                         | Off                                                                         |
| ----------------------------------- | -------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| Anchorage area                      | ![settings](../img/anchorage-area_on.png  "settings")                      | ![settings](../img/anchorage-area_off.png  "settings")                      |
| Beacon special purpose/general      | ![settings](../img/beacon-special-purpose-general_on.png  "settings")      | ![settings](../img/beacon-special-purpose-general_off.png  "settings")      |
| Building single                     | ![settings](../img/building-single_on.png  "settings")                     | ![settings](../img/building-single_off.png  "settings")                     |
| Built-up area                       | ![settings](../img/built-up-area_on.png  "settings")                       | ![settings](../img/built-up-area_off.png  "settings")                       |
| Buoy cardinal                       | ![settings](../img/buoy-cardinal_on.png  "settings")                       | ![settings](../img/buoy-cardinal_off.png  "settings")                       |
| Buoy isolated danger                | ![settings](../img/buoy-isolated-danger_on.png  "settings")                | ![settings](../img/buoy-isolated-danger_off.png  "settings")                |
| Buoy lateral                        | ![settings](../img/buoy-lateral_on.png  "settings")                        | ![settings](../img/buoy-lateral_off.png  "settings")                        |
| Buoy special purpose/general        | ![settings](../img/buoy-special-purpose-general_on.png  "settings")        | ![settings](../img/buoy-special-purpose-general_off.png  "settings")        |
| Cable submarine                     | ![settings](../img/cable-submarine_on.png  "settings")                     | ![settings](../img/cable-submarine_off.png  "settings")                     |
| Caution area                        | ![settings](../img/caution-area_on.png  "settings")                        | ![settings](../img/caution-area_off.png  "settings")                        |
| Crane                               | ![settings](../img/crane_on.png  "settings")                               | ![settings](../img/crane_off.png  "settings")                               |
| Depth contour                       | ![settings](../img/depth-contour_on.png  "settings")                       | ![settings](../img/depth-contour_off.png  "settings")                       |
| Dregded area                        | ![settings](../img/dregded-area_on.png  "settings")                        | ![settings](../img/dregded-area_off.png  "settings")                        |
| Dumping ground                      | ![settings](../img/dumping-ground_on.png  "settings")                      | ![settings](../img/dumping-ground_off.png  "settings")                      |
| Ferry route                         | ![settings](../img/ferry-route_on.png  "settings")                         | ![settings](../img/ferry-route_off.png  "settings")                         |
| Harbour facility                    | ![settings](../img/harbour-facility_on.png  "settings")                    | ![settings](../img/harbour-facility_off.png  "settings")                    |
| Land region                         | ![settings](../img/land-region_on.png  "settings")                         | ![settings](../img/land-region_off.png  "settings")                         |
| Landmark                            | ![settings](../img/landmark_on.png  "settings")                            | ![settings](../img/landmark_off.png  "settings")                            |
| Magnetic variation                  | ![settings](../img/magnetic-variation_on.png  "settings")                  | ![settings](../img/magnetic-variation_off.png  "settings")                  |
| Marine farm/culture                 | ![settings](../img/marine-farm-culture_on.png  "settings")                 | ![settings](../img/marine-farm-culture_off.png  "settings")                 |
| Navigation line                     | ![settings](../img/navigation-line_on.png  "settings")                     | ![settings](../img/navigation-line_off.png  "settings")                     |
| Offshore production area            | ![settings](../img/offshore-production-area_on.png  "settings")            | ![settings](../img/offshore-production-area_off.png  "settings")            |
| Pilot boarding place                | ![settings](../img/pilot-boarding-place_on.png  "settings")                | ![settings](../img/pilot-boarding-place_off.png  "settings")                |
| Recommended track                   | ![settings](../img/recommended-track_on.png  "settings")                   | ![settings](../img/recommended-track_off.png  "settings")                   |
| Restricted area                     | ![settings](../img/restricted-area_on.png  "settings")                     | ![settings](../img/restricted-area_off.png  "settings")                     |
| Road                                | ![settings](../img/road_on.png  "settings")                                | ![settings](../img/road_off.png  "settings")                                |
| Sea area/Named wate -area           | ![settings](../img/sea-area-named-water-area_on.png  "settings")           | ![settings](../img/sea-area-named-water-area_off.png  "settings")           |
| Silo/Tank                           | ![settings](../img/silo-tank_on.png  "settings")                           | ![settings](../img/silo-tank_off.png  "settings")                           |
| Swept area                          | ![settings](../img/swept-area_on.png  "settings")                          | ![settings](../img/swept-area_off.png  "settings")                          |
| Topmark                             | ![settings](../img/topmark_on.png  "settings")                             | ![settings](../img/topmark_off.png  "settings")                             |
| Traffic separation scheme Lane-part | ![settings](../img/traffic-separation-scheme-lane-part_on.png  "settings") | ![settings](../img/traffic-separation-scheme-lane-part_off.png  "settings") |
| Traffic separation zone             | ![settings](../img/traffic-separation-zone_on.png  "settings")             | ![settings](../img/traffic-separation-zone_off.png  "settings")             |
| Unsurveyed area                     | ![settings](../img/unsurveyed-area_on.png  "settings")                     | ![settings](../img/unsurveyed-area_off.png  "settings")                     |
| Wreck                               | ![settings](../img/wreck_on.png  "settings")                               | ![settings](../img/wreck_off.png  "settings")                               |

### Depths

In the examples above there is three colors representing the depths, white, light blue and dark blue. In OpenCPN you can choose 2 or 4 colors to represent depth. The look in the examples is achieved by setting the safe depth to a high number, e.g. 1000 m and shallow depth to e.g. 3  m and deep depth to e.g. 6 m. Adjust to your needs.

### Fonts

The font settings are not included in the files of this repository. In Options -> User Interface you can choose the font of your liking. In the examples the "ENC Sounding Factor" is set to -3 to reduce the font size of the sounding numbers in the charts.
