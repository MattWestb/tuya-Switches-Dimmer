# tuya-Switches-Dimmer

First out is dula dimmer without neutrale lal QS-Zigbee-D02-TRIAC-2C-L



ZH Device info:
```
TS110F
by _TZ3000_92chsky7
Silicon Labs EZSP
Zigbee info
IEEE: 60:a4:23:ff:fe:80:11:a0
Nwk: 0x5454
Device Type: Router
LQI: 164
RSSI: -59
Last Seen: 2021-07-04T20:39:08
Power Source: Mains
```

Zigbee Device Signature:
```
2021-07-04 21:50:27 DEBUG (MainThread) [zigpy.zcl] [0x5454:1:0x0019] OTA query_next_image handler for '_TZ3000_92chsky7 TS110F': field_control=0, manufacture_id=4098, image_type=5634, current_file_version=66, hardware_version=None

{
  "node_descriptor": "NodeDescriptor(logical_type=<LogicalType.Router: 1>, 
complex_descriptor_available=0, 
user_descriptor_available=0, 
reserved=0, 
aps_flags=0, 
frequency_band=<FrequencyBand.Freq2400MHz: 8>, 
mac_capability_flags=<MACCapabilityFlags.AllocateAddress|RxOnWhenIdle|MainsPowered|FullFunctionDevice: 142>, manufacturer_code=4098, 
maximum_buffer_size=82, 
maximum_incoming_transfer_size=82, 
server_mask=11264, 
maximum_outgoing_transfer_size=82, 
descriptor_capability_field=<DescriptorCapability.0: 0>, 
*allocate_address=True, 
*is_alternate_pan_coordinator=False, 
*is_coordinator=False, 
*is_end_device=False, 
*is_full_function_device=True, 
*is_mains_powered=True, 
*is_receiver_on_when_idle=True, 
*is_router=True, 
*is_security_capable=False)",
  "endpoints": {
    "1": {
      "profile_id": 260,
      "device_type": "0x0101",
      "in_clusters": [
        "0x0000",
        "0x0004",
        "0x0005",
        "0x0006",
        "0x0008"
      ],
      "out_clusters": [
        "0x000a",
        "0x0019"
      ]
    },
    "2": {
      "profile_id": 260,
      "device_type": "0x0101",
      "in_clusters": [
        "0x0004",
        "0x0005",
        "0x0006",
        "0x0008"
      ],
      "out_clusters": []
    }
  },
  "manufacturer": "_TZ3000_92chsky7",
  "model": "TS110F",
  "class": "zigpy.device.Device"
}
```

