# GNSS-SDR

## SOFTWARE USADO

### GNU-Radio
Es un kit de herramientas de código abierto gratuito que proporciona una gran diversidad de bloques de procesamiento de señales para implementación de radios de software, el cual puede ser utilizado con otros dispositivos receptores para crear radios definidas por software o versiones simuladas. Este software se utiliza en entornos de la industria e investigación.

![alt text](https://raw.githubusercontent.com/JhonKyG/GNSS-SDR/Document/Images/GNU-radio.png)

### GNSS-SDR PROJECT

Then, GNSS-SDR takes care of all the digital signal processing, performing signal acquisition and tracking of the available satellite signals, decoding the navigation message, and computing the observables needed by positioning algorithms, which ultimately compute the navigation solution. The software is designed to facilitate the inclusion of new signal processing techniques, offering an easy way to measure their impact on the overall receiver performance. Testing of all the processes is conducted both by the systematic functional validation of every single software block and by experimental validation of the complete receiver using either real-time signals received by the radio frequency front-end or a file containing those raw signal samples.

![alt text](https://repository-images.githubusercontent.com/18740094/9338ab00-a06f-11ea-8e2b-d236bf2327e7)

## HARDWARE USADO

### HackRF One

Es un dispositivo auxiliar e independiente utilizado por SDR para transmitir o recibir señales de radio desde 1 MHZ hasta 6 GHZ. Diseñado para facilitar el desarrollo de las tecnologías de la comunicación tanto actuales como en el desarrollo de las nuevas generaciones de tecnologías de radio junto con sus correspondientes protocolos de comunicación.

![alt text](https://raw.githubusercontent.com/JhonKyG/GNSS-SDR/Document/Images/HackRF_One.jpg)

### RTL-SDR

RTL-SDR is a very cheap ~$25 USB dongle that can be used as a computer based radio scanner for receiving live radio signals in your area (no internet required). Depending on the particular model it could receive frequencies from 500 kHz up to 1.75 GHz. Most software for the RTL-SDR is also community developed, and provided free of charge.

The origins of RTL-SDR stem from mass produced DVB-T TV tuner dongles that were based on the RTL2832U chipset. With the combined efforts of Antti Palosaari, Eric Fry and Osmocom (in particular Steve Markgraf) it was found that the raw I/Q data on the RTL2832U chipset could be accessed directly, which allowed the DVB-T TV tuner to be converted into a wideband software defined radio via a custom software driver developed by Steve Markgraf. If you've ever enjoyed the RTL-SDR project please consider donating to Osmocom via Open Collective as they are the ones who developed the drivers and brought RTL-SDR to life.

![alt text](https://www.passion-radio.com/2301-large_default/rtlsdr-tcxo.jpg)

### NOOELEC LNA

Nooelec LaNA is a very high performance, wideband LNA module designed for general purpose SDR applications.

![alt text](https://m.media-amazon.com/images/I/81cKXfCutBL._AC_SY355_.jpg)
