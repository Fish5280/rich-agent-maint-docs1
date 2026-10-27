# SOP: Resetting a Drive Motor Thermal Trip

Procedure SOP-MNT-014, Toledo local revision (not approved). Applies to all screw drive motors (part number IMM-DRV-15KW) at every
Skyline Plastics plant. Owner: Maintenance lead.

## 1. Purpose
A thermal trip means the motor's thermal protector opened the contactor to protect the winding. Resetting
without finding the cause shortens winding life and usually leads to a repeat trip. This procedure sets the
minimum checks before a reset.

## 2. Who may reset
- A qualified maintenance technician.
- Operators may not reset a drive motor thermal trip.
- On night shift, the on-call technician resets; the shift supervisor records the event.

## 3. Cool-down
- Do not reset until the winding has cooled below 80 C. This applies to both makes (Voltrix VX-15 and
  AcmeDrive AD-15K).
- Read the winding temperature on the drive display. If the display is not available, wait at least
  45 minutes and confirm with a handheld infrared reading at the frame.
- Never force cooling with compressed air or water.

## 4. Checks before reset
Work through these in order and write down what you find:
1. Ambient: read the zone air temperature near the motor and compare it with the rated ambient in the
   motor's manual (VX-15: 30 C; AD-15K: 40 C). Check for open HVAC facility work orders on the zone.
2. Ventilation: fan cowl clean, fan turns freely, 300 mm clearance around the cowl.
3. Lubrication: look up the last completed lubrication and compare it with the manual interval. A missed
   or deferred lubrication must be raised with the maintenance lead before the motor returns to full load.
4. Load: check the current product and shift pattern against the production schedule.
5. Bearings: listen for roughness and look for rpm fluctuation in the sensor data.

## 5. Reset
- Apply lockout/tagout (SOP-SAF-002) before opening the terminal box or the fan cowl.
- Remove the lock, reset the protector at the drive, and run the motor at low speed for 10 minutes.
- Watch the winding temperature for the first 30 minutes at normal load.

## 6. Repeat trips
- A second trip within 7 days on the same motor: do not reset again without the maintenance lead.
- Three trips within 30 days: the motor is taken out of service for inspection, and a corrective record is
  raised.

## 7. Records
- Record every trip and reset in the maintenance system as a corrective record with task
  "thermal trip reset", the time, the winding temperature at reset and the checks done.
- If the trip coincides with a zone temperature problem, record both in the shift log (see the plant's
  HVAC zones note).

## 8. Related documents
- Voltrix VX-15 service manual (VX15-SM-04), AcmeDrive AD-15K service manual (AD15K-SM-11).
- Troubleshooting: Motor Overheating.
- Lockout/Tagout SOP-SAF-002.
- PM Deferral Policy PM-007.
