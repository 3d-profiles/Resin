# Resin

In this directotory will be stored the profiles for different resin brands for each printer and tools for a successful calibration.

Printers:
- Anycubic Photon Mono

Resin Brands:
- Sunlu

Tools:
- Calibration cube (pending to upload)

# Provisioning rules
Each config file will be stored wieh the resin brand first and the printer brand and model later. File will be stored in the printers' directory and will be linked from the resin's directory. Like this:
├── Printers
│   └── Photon_Mono
│       └── Sunlu_Photon_Mono.conf
├── README.md
└── Resin
    └── Sunlu
        └── Sunlu_Photon_Mono.conf -> ../../Printers/Photon_Mono/Sunlu_Photon_Mono.conf


