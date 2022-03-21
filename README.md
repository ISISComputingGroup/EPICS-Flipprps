# EPICS Flipprps

The CRISP Spin Flipper is generally referred to as 'FLIPPRPS' in IOC and support files. It is a simple device for running polarised neutron experiments that can be set to either "up" or "down", presumably to polarise neutrons in one of those directions. The IOC is a stream device.

## WIKI
Please see the WIKI for more information on the CRISP spin flipper:
- https://github.com/ISISComputingGroup/ibex_developers_manual/wiki/CRISP-Spin-Flipper

## System Tests
The CRISP spin flipper system tests are located in the [EPICS-IOC_Test_Frameork](https://github.com/ISISComputingGroup/EPICS-IOC_Test_Framework): `EPICS-IOC_Test_Framework\tests\spinflipper.py`

To run the system tests, run the following command from and EPICS Terminal (`C:\Instrument\Apps\EPICS\config_env.bat`): `python run_tests.py -t spinflipper`.

Use the `-a` flag if you want to run the CRISP spin flipper emulator for manual testing.
