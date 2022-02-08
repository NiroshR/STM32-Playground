# Playground

## Formatting
We will use UNIX formatting which also means the carriage-return character we
will use will not be the DOS format.

To make sure we arent' introducing any `^M` characters for newlines, run the 
following command in a UNIX terminal (ex. WSL):

```bash
dos2unix <filename>

# Alternatively open file in Vim
:e ++ff=dos         # tells Vim to read file forcing DOS format
:set ff=unix        # read again forcing UNIX format
:wq                 # save and exit
```

## Useful Links
https://deepbluembedded.com/stm32-timer-interrupt-hal-example-timer-mode-lab/
https://www.digikey.ca/en/maker/projects/getting-started-with-stm32-working-with-adc-and-dma/f5009db3a3ed4370acaf545a3370c30c
https://deepbluembedded.com/stm32-debugging-with-uart-serial-print/
https://ftdichip.com/drivers/vcp-drivers/
https://www.dailyduino.com/index.php/2020/06/01/stm32-can-bus/
https://www.youtube.com/watch?v=e0CP2IpIBg4&ab_channel=IOTES
https://www.electronicshub.org/getting-started-with-stm32f103c8t6-blue-pill/
https://www.electronicshub.org/how-to-upload-stm32f103c8t6-usb-bootloader/
https://idyl.io/arduino/how-to/program-stm32-blue-pill-stm32f103c8t6/
