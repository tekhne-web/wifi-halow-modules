# TEKHNĒ Wi-Fi HaLow Modules Data Files

## Notice

> [!CAUTION]
> The data files released here is specifically designed for the TEKHNĒ Wi-Fi HaLow Modules.

## Directories

```
 .
 └── <module>        # Module name
     └── <variant>   # Country code variant
         └── bdf     # Board Data Files
```

## Board Data Files

The board data files contain RF configuration parameters to comply with different regulations that limit both maximum RF output power and human exposure to RF radiation.

* The files ending in `_ext_ant.dat` contain the appropriate parameters for using the modules with an external antenna. The maximum antenna gain, including cable loss, in a mobile-only exposure condition should not exceed a specified value. Please refer to the datasheet for the particular variant of the Wi-Fi HaLow module to determine the maximum allowable gain value.

* The files ending in `_int_ant.dat` contain the appropriate parameters for the use of modules with the built-in internal antenna.