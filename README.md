# Low Pass Filter PCB

## Instructions

Use only NPO/C0G capacitors. Note the voltage rating. I'm using only 1206/0805 C0G 1kV capacitors.

Photos of results measured with NanoVNA are in /img directory.

Amidon/Micrometals toroids (material 2 and 6) should work out of the box. Alternatives may work too, try them and measure with NanoVNA.

## lpf_qrplabs_3inductors

![lpf3inductors](/lpf_qrplabs_3inductors/board.png)

Use values from https://qrp-labs.com/lpfkit.html

## lpf_2inductors

![lpf2inductors](/lpf_2inductors/board.png)


Use values from http://www.profimot.pl/sp2fp/LPF_HF_50wat/LPF_HF_50wat_sp2fp.html

## lpfserialresonance1 and bs170driver_with_series_resonance_lpf

![trusdx_lpf](/bs170driver_with_series_resonance_lpf/board.png)
![trusdx_lpf](/lpfserialresonance1/board.png)

![bs170photo](/img/IMG_7400.jpeg)

5-6W at lower bands; 2-3W at 10m. Should be driven by 74ACT00 gate for full power.

Use values from (tr)uSDX project, e.g. https://dl2man.de/wp-content/uploads/2022/10/truSDX_Main-RF_Boards_with_Notes_v1.0n.pdf

Note: for some reason, T37-X cores work better than T50-X (with the same inductance) - reason unknown, but this forces using smaller copper wire.

