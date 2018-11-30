# Free Design Solar box 
C'est un projet opensource pour faciliter l'accés l'énèrgie. Il fut inpirer du projet [Libre Solar Box](https://github.com/CollectiveOpenSourceHardware/LibreSolarBox) et  [Libre Solar MPPT Charger](http://libre.solar/devices/mppt-charger/). 

### Voici l'une vue d'ensemble du systeme

![systeme](/FreeDesignSolarBox.png)

### Specification
- P_max_input = 150Wp
- V_max_input = 55V
- V_out_1 = 12V
- V_out_2 = 5V (USB)
- I_max_out = 10A
- I_max_USB = 2A

### Modular, flexible, fully open source
La capacité de la batterie est channger. Il est aussi possible unitilisé batterie en base Li-ion avec un BMS.
Parceque le regulator, le coeur de le system est open source, il est possible de changer le software d'utilisé un autre energy source en basis de DC (current directement, current cintinu - CC). Par example il est aussi d'utilisé an DC-bycicle generator ou puissince vent si un rectifier est installé avant le regulator.
