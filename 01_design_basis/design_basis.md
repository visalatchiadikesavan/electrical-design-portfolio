# Design Basis (Part 1)

## 1. Supply
- Supply type: own transformer substation, about 250 kVA
- Transformer connects to the medium-voltage grid (typically 10 kV in Lithuania)
- Low voltage side: 230/400 V, 50 Hz
- Earthing system: TN-S
- Main LV switchboard: 1

## 2. Standards
- Installations: IEC / LST HD 60364
- Lighting: LST EN 12464-1
- Power quality: EN 50160
- Grid connection: ESO (Lithuanian grid operator) rules

 ## 3. Design targets
- Building installed load: 220 kW
- Building maximum demand: 150 kW (diversity factor about 0.7)
- EV charging: 3 x 22 kW = 66 kW
- Total maximum demand: 216 kW
- Power factor: 0.95 or better
- Total apparent power: 216 / 0.95 = about 227 kVA
- Transformer: 250 kVA, loaded to about 91%
- PV is not counted when sizing the transformer (no output at night)
- Voltage drop: 3% or less for lighting, 5% or less for other circuits
- Final circuits must disconnect within 0.4 s in a fault
- Earth electrode resistance: 10 ohm or less
- Voltage THD: under 8% (design goal under 5%)

## 4. Decisions made
- EV chargers are added on top of the building load, not included in it
- EV chargers reduced from 4 to 3 to keep the 250 kVA transformer
- EV load management is included as protection against overload
