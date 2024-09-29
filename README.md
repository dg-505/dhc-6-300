# dhc6-300

Simulation of the DHC-6-300 Twin Otter for the Flight Gear flight simulator.

## Credits (Original)
* Syd Adams (syd_cyyf):             Initial model, 3D modelling, Textures, FDM, Sound, Systems,
                                    Nasal scripting, etc.
* Christian Thiriot (PATTEN):       Texturing, 3D Modelling, Instruments, etc.
* Bo Lan (lanbo64):                 Systems, Nasal scripting, FDM, Autopilot, Instruments, etc.
* Jonathan Schellhase (dg-505):     Current maintenance, 3D modelling, Systems, Checklists, Tutorials,
                                    Sound, Nasal, 2D panel, Artwork, etc.
* Tim Dicus (SurferTim):            Engine upgrade, autopilot, nasal, etc.

Other contributors:
Clément de l'Hamaide, (f-jjth), PAF Team, Zdenal, Erik, abassign, primtala2,
tauchergreg: Intensive bug hunting, Adam Swift (Mig29pilot): Artwork,
Sebastian (rollershutter), Adrian Serrano (asr), the whole FlightGear community

Special thanks to Thorsten Renk for giving us the wonderful effects of
the ALS framework and to the Cessna 172P development team for the
pioneering work they did regarding the securing procedures and the
environment sounds!


## Technical Specifications

These are the data points collected on the Twin Otter that form the basis of our 
simulation. Wherever possible, these data points should have a minimum of two, ideally three,
reliable sources, with one being authoritative.


_This is for a DHC-6-300 with two PT6A-27 engines_

| Data                                           | Value | Source |
|------------------------------------------------|-------|--------|
| Stall Speed VS1 (Clean Configuration, No Flaps)|       |        |
| Maximum Takeoff Weight                         | 5670kg  | (2),(5)    |
| Empty Weight                                   | 3363kg  | (6) pg. 100 |
| Length                                         | 15.77m|    (6) pg. 100   |
| Height                                         | 5.94m     | (6) pg. 100            |
| Wingspan                                       | 19.812m      | (6) pg. 100           |
| Wing Area                                      | 39m²|    (6) pg. 100   |

| Moment of Intertia (x-axis)                    |       |             |


## Reference Data
Several hundred pages of real-world technical information on the Twin Otter has been collected and archived on the Internet Archive.

1. [Standard Operating Procedures](https://web.archive.org/web/20170224162942/https://www.blm.gov/style/medialib/blm/nifc/av.Par.70826.File.tmp/SOPA_otter.pdf)
2. [FAA Type Certificate Data Sheet (2018)](https://ia804507.us.archive.org/4/items/a-9-ea-rev-21/A9EA_Rev_21.pdf)
3. [Twin Otter Pilot Training Manual Series 100/200/300](https://ia803205.us.archive.org/28/items/dhc-6-ptm/DHC-6%20Pilot%20Training%20Materials/DHC-6%20PTM.pdf)
4. [Pratt & Whitney PT-6A Pilot Familiarization](https://web.archive.org/web/20200719205147/https://rwrpilottraining.com/uploads/3/0/3/7/3037605/pt6_pilot_familiarization.pdf)
5. [Airliners.net](https://web.archive.org/web/20240706165434/https://www.airliners.net/aircraft-data/de-havilland-canada-dhc-6-twin-otter/181)
6. [The International Directory Of Civil Aircraft](https://archive.org/details/internationaldir0000fraw_q7f4/)

### Performance data

| Aircraft Model | Document Link            |
|----------------|--------------------------|
| **DHC6-300 (this aircraft)**   | [PSM-1-63-1A (Section 4)](https://web.archive.org/web/20170324171425/http://www.caamsllc.com/Performance%20Data/DHC-6-300.pdf)    |
| DHC6-200       | [PSM-1-62-1A (Section 4)](https://web.archive.org/web/20170324040942/http://www.caamsllc.com:80/Performance%20Data/DHC-6-200.pdf) |
| DHC6-100       | [PSM-1-61-1A (Section 4)](https://web.archive.org/web/20170324100753/http://www.caamsllc.com:80/Performance%20Data/DHC-6-100.pdf) |
