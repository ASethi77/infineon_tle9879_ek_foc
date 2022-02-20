# TLE9879_EVAL_BLDC_Control
Field-oriented control demonstration on the Infineon TLE9879 evaluation board. 

## A note on the toolchain
*NOTE -* This project uses the Zephyr RTOS and `west` build system. Please follow the installation instructions
over at the Zephyr docs to ensure you have the toolchain installed. Further, this application is based on the
[Zephyr example application](https://github.com/zephyrproject-rtos/example-application).

```
https://github.com/ASethi77/infineon_tle9879_ek_foc.git --mr main infineon_eval_foc
cd infineon_eval_foc
west update
```


## PyOCD

Make sure you have `pyocd` installed through pip, and that you have the TLE9879 CMSIS pack installed:

```
pyocd pack install TLE9879QXA40
```