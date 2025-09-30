# RAKKA 60 ATLAS Design Files

## Plate Drawings

- **plate_pcb_mount_stab_all_layout_compatiable.dxf**

  Drawings of plates that compatible with PCB-mount stabilizers.

  All layout options supported.

  In addition to the screw holes corresponding to the GH60, there are also screw holes for the standoffs used to secure the plate and the PCB.

- **plate_plate_mount_stab_625_space.dxf**
- **plate_plate_mount_stab_625_split_space.dxf**
- **plate_plate_mount_stab_700_space.dxf**
- **plate_plate_mount_stab_700_split_space.dxf**

  Drawings of plates that compatible with plate-mount stabilizers.

  All of them have the layout options fixed.

  In addition to the screw holes corresponding to the GH60, there are also screw holes for the standoffs used to secure the plate and the PCB. For 6.25u and 7.00u spacebars, there are also openings for the light guide posts of the spacebar LEDs. Please refer to the actual product.

## 3D Models

> **Notes:**
> 
> All 3D models are for reference only, with most components removed. Please refer to the real product.
> 
> The thickness of the PCB has a tolerance.

### Assembled

- **3d_assembled.step**

  Assembled model for this configuration:
  - Plate for plate mount stabilizers and 625U space
  - LED back panel for 625U space
  - Daughterboard for GH60 cases (3d_daughterboard_gh60.step)
  
  This allows case designers to check compatibility.

### Mainboard

- **3d_mainboard.step**

  Main PCB model. Most components are removed.

### LED Back Panels

- **3d_led_back_panel_625_split.step**
- **3d_led_back_panel_625.step**
- **3d_led_back_panel_700_split.step**
- **3d_led_back_panel_700.step**

### Daughterboards

#### For GH60

- **3d_daughterboard_gh60.step**
  
  Making GH60 USB connector to a removable daughterboard.

#### For others

The final released products _may_ be subject to change.

- **3d_daughterboard_adapter.step**

  Adapter board installed on the position of GH60 USB connector.

- **3d_UDB-C.step**

  UDB-C board with Molex 781710004 connector.
