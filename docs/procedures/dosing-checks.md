# Chemical Dosing Checks

Automated SCADA readings must be physically verified once per shift to ensure feed pumps are accurate.

## Verification Procedure (Drawdown Test)
This test confirms the actual mL/min output of a chemical pump.

1.  **Isolate:** Close the valve from the bulk tank to the calibration column.
2.  **Fill:** Open the column fill valve to fill the calibration tube.
3.  **Run:** Let the pump draw from the column for exactly **1 minute**.
4.  **Measure:** Record the mL dropped in the column.
5.  **Calculate:** $$\text{Feed Rate (GPH)} = \frac{\text{mL/min} \times 0.0158}{1}$$

## Tank Level Inspections
Check physical tank levels against SCADA.

* [ ] **Sodium Hypochlorite:** Verify day tank level matches ultrasonic sensor.
* [ ] **PAC (Polymer):** Visually inspect mixing energy in the day tank.
* [ ] **Fluoride:** Ensure saturator tank has visible crystals (undissolved salt) at the bottom.

!!! warning "Air Lock"
    If a pump is running but the flow meter reads zero, the pump head may be air-locked. Follow the *Pump Priming SOP*.