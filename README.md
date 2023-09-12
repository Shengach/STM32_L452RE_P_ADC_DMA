# STM32_L452RE_P_ADC_DMA

This project is for the amplitude readout of Dielectric Spectroscopy System. 
Please enable the ADC1, and connect the LPF_Cap to PC0. 
In the parameter setting of ADC1, please enable the following mode: 
1. Continuous Conversion Mode
2. DMA Continuous Requests
3. Enable Regular Conversion

Besides, please add the ADC1 to DMA Request of DMA1 and turn on the circular mode.
