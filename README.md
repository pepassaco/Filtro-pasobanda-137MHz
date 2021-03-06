# Filtro paso banda para 137MHz
Filtro diseñado para trabajar adecuadamente la banda de 2m (VHF). Capaz de cubrir tanto la zona destinada a comunicaciones entre radioaficionados (144MHz-148MHz) como la asociada a los satélites NOAA 15, 18, 19 y Meteor M N2-1 (137MHz-138MHz). 

![alt text](https://raw.githubusercontent.com/pepassaco/Filtro-pasobanda-137MHz/master/Simulaciones/2.jpg)

# Características:

- Tipo de filtro: paso banda, Butterworth modificado para mejor S11 en banda de paso

- Orden: 6

- Frecuencia de corte inferior: 125MHz

- Frecuencia de corte sueprior: 155MHz

- Atenuación banda radiodifusión FM: >50dB

- Inpedancia de entrada: 50Ω

- Inpedancia de salida: 50Ω

**Note**: on the PCB, the 6th stage of the filter includes space for a second inductor. This es due to the unavailability of an inductor of the esact value I needes, so I ended up dividing it into two that added up the original value.
