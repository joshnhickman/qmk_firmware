# joshnhickman's planck v6 drop layout

https://qmk.fm/keyboards/planck/
https://config.qmk.fm/#/test/

TODO tapdance 
https://docs.qmk.fm/#/feature_tap_dance?id=example-4
https://github.com/qmk/qmk_firmware/tree/master/users/gordon

## compile and flash

open the qmk terminal, then:
```bash
qmk compile -kb planck/rev6_drop -km joshnhickman
qmk flash -kb planck/rev6_drop -km joshnhickman
```
lower+raise+q for QK_BOOT (reset)  
test https://config.qmk.fm/#/test/


https://docs.qmk.fm/#/newbs_building_firmware
https://docs.qmk.fm/#/newbs_flashing
