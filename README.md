<div>
<p align="center">
<a href="https://www.pixilart.com/art/usbkiller-sr2357abcd61f96" >
  <img width="200" src="https://i.postimg.cc/0N19M2bg/sr2357abcd61f96.png" alt="Course Hero logo">
</a>
  </p>  
<h1 align="center">
  usb killer
</h1>
<p align="center">
Welcome to the world of high voltage
</p>
</div>

_This project is sponsored by [SUSTech-EE201-17L](https://nces.cra.moe/course/286/) as a DIY projecy._ 

[![GitHub license](https://img.shields.io/github/license/drinktoomuchsax/usb-killer)](https://github.com/drinktoomuchsax/usb-killer/blob/main/LICENSE)      [![GitHub stars](https://img.shields.io/github/stars/drinktoomuchsax/usb-killer?style=social)](https://github.com/drinktoomuchsax/usb-killer/stargazers/)

---

# How build your own usbkiller
## Schematic
The schematic is drawed using JLC eda, you can [view the killer schematic on oshwHub](https://oshwhub.com/drinktoomuchsax/usb_killer_ac-version) or below.

![schematic](killerSchematic.png)

## PCB 
You can use [the gerber file](killerGerber.zip) to manufacture the pcb
## BOM

| Name                  | Value                 | Purchase link | Comment |
| --------------------- | --------------------- | ------------- | ------- |
| Capacitor(0603)       | 10uF\*2, 100pF\*1     | [taobao]()    |         |
| Resistor(0603)        | 1k ohm\*2,1.2k ohm\*1 | [taobao]()    |         |
| LED(0805)             | RED\*1, GREEN\*1      | [taobao]()    |         |
| Transistor            | IRFZ44NPBF\*1         | [taobao]()    |         |
| Switch                | TS665TP 250gf 013c    | [taobao]()    |         |
| Transformer           | diy type on taobao    | [taobao]()    |         |
| Power management chip | TP4056                | [taobao]()    |         |
| USB port              |                       | [taobao]()    |         |
| Diode                 | DO_1N4007             | [taobao]()    |         |

## Soldering

Follow this map to solder.
## Test

# How this works

# TO-DO

- [ ] redesign the pcb making it both circuits board and shell
- [x] writing a doc

# Q&A
**Is this safe to human?**
> yes, i have test the killer on myself and lots of my friends. It just hurts a lot, but no obvious burning scar left

**Can I turn the design into even more powerful one?**  
> yes, the output voltage could be easily boost into thousands of voltage by using more powerful battery and add more boost circuits
