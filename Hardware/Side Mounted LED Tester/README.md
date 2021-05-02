# Side Mounted LED Tester Board

![image](https://user-images.githubusercontent.com/1562562/116828351-12930080-ab96-11eb-8102-9219d0f20d12.png)
![image](https://user-images.githubusercontent.com/1562562/116828356-19ba0e80-ab96-11eb-8ee9-e8891640c7af.png)


I designed this board to test using side mounted LEDs for shining through the Fr4 material of the PCB, it got a decent response on twitter with a lot of questions, so I thought this might help! The board was never intended to be for anything other than personal use so it's kind of a mess, but hopefully it will be useful to someone!

The board has 12 Charlieplexed LEDs connected to a header pin (8x1, but 2 pins per connection). Check out [this video for more information on Charlieplexing](https://www.youtube.com/watch?v=b44VGTaCSk8)

## Help Support what I do!

My main contribution to the open source community to date has been my Arduino libraries for the ESP32 and ESP8266, but have lately been trying to contribute more on the hardware side of things.

[If you enjoy my work, please consider becoming a Github sponsor!](https://github.com/sponsors/witnessmenow/)

## LEDs Used:

![image](https://user-images.githubusercontent.com/1562562/116828376-39e9cd80-ab96-11eb-90bb-3c067b115a52.png)


The LEds I used are 3.2x1.5mm side mounted LEDs, but LCSC filter for these absolutely sucks, so here is a list of all the ones I have tried in descending order of how bright I thought they were (brightest first)

| Name                          | Colour | Source                                                                                                       | Comment                                           |
| ----------------------------- | ------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------- |
| TOGIALED TJ-S3210SW5TGLC2G-A5 | Green  | [LCSC](https://lcsc.com/product-detail/Light-Emitting-Diodes-LED_TOGIALED-TJ-S3210SW5TGLC2G-A5_C273630.html) | Very good                                         |
| TOGIALED TJ-S3210SW5TGLC2R-A5 | Red    | [LCSC](https://lcsc.com/product-detail/Light-Emitting-Diodes-LED_TOGIALED-TJ-S3210SW5TGLC2R-A5_C273626.html) | Very good                                         |
| TOGIALED TJ-S3210SW5TGLC0A-A5 | Orange | [LCSC](https://lcsc.com/product-detail/Light-Emitting-Diodes-LED_TOGIALED-TJ-S3210SW5TGLC0A-A5_C273627.html) | Decent, Pretty similar colour to above Red though |
| TOGIALED TJ-S3210SW5TGLC6B-A5 | Blue   | [LCSC](https://lcsc.com/product-detail/Light-Emitting-Diodes-LED_TOGIALED-TJ-S3210SW5TGLC6B-A5_C273631.html) | OK                                                |
| TOGIALED TJ-S3210SW5TGLC9Y-A5 | Yellow | [LCSC](https://lcsc.com/product-detail/Light-Emitting-Diodes-LED_TOGIALED-TJ-S3210SW5TGLC9Y-A5_C273628.html) | Not great                                         |
| Lite-On LTST-S110KSKT         | Yellow | [LCSC](https://lcsc.com/product-detail/Light-Emitting-Diodes-LED_Lite-On-LTST-S110KSKT_C115449.html)         | Not as bright as the TOGIALED one                 |
| EKINGLUX E6C1204CWAY1UDA      | White  | [LCSC](https://lcsc.com/product-detail/Light-Emitting-Diodes-LED_EKINGLUX-E6C1204CWAY1UDA_C375483.html)      | Not impressive                                    |

## Open Source

This project was designed using EasyEDA and the entire project is shared here at [this link](https://oshwlab.com/ecenuig/sidemounttester).

The schematic and gerber files for this board can be found in this folder.

This project is licensed under the CERN Open Hardware License V1.2. Details of the license can be found in license.md at the root of the repo.

## PCB Details

I used just regular ol 1.6mm PCB. I guess thinner PCBs would be brighter, but would diffuse less.
