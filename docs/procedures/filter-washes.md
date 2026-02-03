# Filter Backwash Procedure

Filters must be washed when they reach terminal headloss, turbidity breakthrough, or a run time of 72 hours.

## Pre-Wash Checklist
* [ ] Ensure **Backwash Tank** is full (> 20 ft).
* [ ] Verify **Air Scour Blower** is available.
* [ ] Check **Waste Gullet** gate is clear.

## Automatic Wash Sequence
Initiate "Auto-Wash" on the SCADA panel. The system will cycle through:

1.  **Drain Down:** Level drops to 6 inches above media.
2.  **Air Scour:** Air is injected for 3 minutes to break up the mud ball layer.
3.  **Low Wash:** Water enters at 2,000 gpm to fluidize the bed.
4.  **High Wash:** Flow increases to 8,000 gpm to flush solids to the trough.
5.  **Settle:** 2-minute pause to let media stratify (sand on bottom, coal on top).

## Post-Wash Validation
After the filter returns to service:
* **Monitor:** Watch the turbidity meter for the first 15 minutes.
* **Filter-to-Waste:** Ensure the valve closes only after turbidity drops below **0.20 NTU**.