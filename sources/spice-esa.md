# ESA/PSA SPICE Kernels

The ESA/PSA spice kernel are available from the [ESA/PSA repository](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS). 
It covers the BEPI-COLOMBO, ExoMars2016, HUYGENS, JUICE, MARS-EXPRESS and ROSETTA missions.

## Bepi-Colombo

| Frame name             | NAIF ID | Definition | Synonyms | Kernel file |
| ---------------------- | ------- | ---------- | -------- | ----------- |
| MMO_SPACECRAFT         | -68000  | Bepi-Colombo MMO (Mio) spacecraft frame | MMO_SC | |

## ExoMars2016

## HUYGENS

## JUICE

| Frame name                 | Center   | NAIF ID | Definition | Synonyms | Kernel file |
| ----------------------     | -------- | ------- | ---------- | -------- | ----------- |
| JUICE_SPACECRAFT           | JUICE    | -28000  | JUICE spacecraft frame | JUICE_SC | |
| JUICE_JUPITER_IF_J2000     | JUPITER  | -28970  | Jupiter Inertial Frame at J2000 | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUICE_JUPITER_MAG_S3RH1965 | JUPITER  | -28971  | Jupiter Magnetic System III VIP4 model using IAU 1994 constants | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUICE_JUPITER_MAG_S3RH2009 | JUPITER  | -28972  | Jupiter Magnetic System III VIP4 model using IAU 2009 constants | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUICE_JSEQ                 | JUPITER  | -28973  | Jovian-centric Equatorial Solar | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUICE_JUPITER_BSM          | JUPITER  | -28974  | Jupiter Solar Magnetospheric | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUICE_JUPITER_SJC          | JUPITER  | -28975  | Solar Joviancentric Coordinates | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUICE_JSM                  | JUPITER  | -28976  | Jupiter Solar Magnetic  | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUICE_JSW                  | JUPITER  | -28977  | Jupiter Solar Wind | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUICE_JSWM                 | JUPITER  | -28978  | Jupiter Solar Wind Magnetospheric | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUICE_CALLISTO_PHI_ORB     | CALLISTO | -28980  | Callisto-centered Phi-Zorb | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUICE_EUROPA_PHI_ORB       | EUROPA   | -28981  | Europa-centered Phi-Zorb | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUICE_GANYMEDE_PHI_ORB     | GANYMEDE | -28982  | Ganymede-centered Phi-Zorb | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUICE_HGRTN                | SUN      | -28990  | JUICE Heliocentric Radial-Tangential-Normal | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUICE_SUN_RTN              | JUICE    | -28991  | Sun-orbit JUICE Radial-Tangential-Normal | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUICE_JUPITER_DM           | JUPITER  | -28992  | Jupiter JUICE Dipole Meridian | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUICE_JUPITER_RTP          | JUPITER  | -28993  | JUICE Jupiter R-Theta-Phi | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUPITER_SYSTEM3RH_1965     | JUPITER  | -28999  | Jupiter System III Right-handed using the IAU 1994 constants | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUPITER_SYSTEM3RH_2009     | JUPITER  | -28998  | Jupiter System III Right-handed using the IAU 2009 constants | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUPITER_MAG_VIP4           | JUPITER  | -28997  | Jupiter Magnetic System III VIP4 | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUPITER_MEQUD              | JUPITER  | 500599000  | Jupiter Mean Equator of date | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUPITER_SUN_EQU            | JUPITER  | 500599001  | Jupiter Solar Equatorial | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUPITER_SUN_ORB            | JUPITER  | 500599002  | Jupiter Solar Orbital | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUPITER_CALLISTO_BCSF      | JUPITER  | 500599006  | Jupiter-centric Callisto-following | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUPITER_EUROPA_BCSF        | JUPITER  | 500599004  | Jupiter-centric Europa-following  | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| JUPITER_GANYMEDE_BCSF      | JUPITER  | 500599005  | Jupiter-centric Ganymede-following | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| CALLISTO_JUPITER_ORB       | CALLISTO | 500504000  | Callisto Orbital | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| EUROPA_JUPITER_ORB         | EUROPA   | 500502000  | Europa Orbital | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |
| GANYMEDE_JUPITER_ORB       | GANYMEDE | 500503000  | Ganymede Orbital | | [juice_sci_v05.tf](https://repos.cosmos.esa.int/socci/projects/SPICE_KERNELS/repos/juice/browse/kernels/fk/juice_sci_v05.tf) |


## Mars-Express

## Rosetta



