# AuroraZ605.Firmware
Aurora Z605 Firmware (Prusa I3)

# EN
This is a firmware that is running on my 3D printer right now. I've made some changes from the original one, found [here](http://www.fennecelectronics.it/2014/08/aurora-3d-printer/), to run smoothly on my printer. All the changes were made on the [Repetier Firmware Tool](https://www.repetier.com/firmware/v100/). 

To flash my Melzi board and upload the firmware, I used [this tutorial](https://www.instructables.com/id/Using-an-Arduino-to-Flash-the-Melzi-Board-Wanhao-I/) as a main path, although the step of setting and running Arduino as ISP, I used this [one](https://www.arduino.cc/en/Tutorial/ArduinoISP)

With this firmware, your printer's board will work as an EEPROM, that means that you'll make the hard process once, and later you can edit some params using your Host software. [Repetier Host](https://www.repetier.com/) has a really good Firmware EEPROM Configuration tool.

# PT

Este é o firmware que está rodando na minha impressora 3D atualmente, fiz algumas mudanças no que encontrei na [aqui](http://www.fennecelectronics.it/2014/08/aurora-3d-printer/), para rodar lisinho na minha impressora. Todas mudanças foram feitas na [Ferramenta de Edição de Firmware da Repetier](https://www.repetier.com/firmware/v100/).

Para resetar a minha placa Melzi e fazer o upload do Firmaware, usei [esse tutorial](https://www.instructables.com/id/Using-an-Arduino-to-Flash-the-Melzi-Board-Wanhao-I/) em geral, porém o passo de configurar e rodar o Arduino como ISP eu usei [este aqui](https://www.arduino.cc/en/Tutorial/ArduinoISP).

Este firmware faz a placa da impressora trabalhar como uma EEPROM, isto é, o processo complicado é feito uma vez só, e depois é possivel ajustar alguns parametros do firmware no seu software de Host. O [Repetier Host](https://www.repetier.com/) tem uma ferramenta de configuração de Firmware EEPROM muito boa.

