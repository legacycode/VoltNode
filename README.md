# VoltNode™
VoltNode™ is a SA818 based UHF/VHF node designed to be compatible with the open source [SVXLink project](https://github.com/sm0svx/svxlink "SVXLink project"). The PCB was designed to fit over the OrangePiZero and the schematic and GPIO choice is based on the original work of the [ROLink community](http://www.439100.ro/ "ROLink community"), with the goal of having this hardware compatible with ready made OS images create by the ROLink community.

More info about this project in [Voltlog #385](https://youtu.be/EprSIw-5l6w).

Known issues in revA: The mic negative input on the orangepizero is left floating which could lead to some input noise being amplified. A fix is indicated in the schematic.

![Image of the assembled PCB](voltnode.JPG)
