# Incident Report – Treasury Breach  

**Date:** September 4, 2025  
**Location:** TechSphere Headquarters – Treasury Wing  
**Report Type:** Internal Case Narrative  

At 00:03 AM, Treasury systems recorded a brief flicker of activity. Alarm indicators flashed, then stabilized. Security staff on duty dismissed it as a transient fault.

Between 12:05 AM and 12:10 AM, movement near the CFO’s office was recorded. Richitha was observed connecting a USB drive to the CFO’s terminal, reportedly to share files. Around the same window, Shaswanth appeared on Treasury corridor CCTV while maintenance logs attributed activity in that area to scheduled IT checks.

At 12:10 AM, the CFO’s workstation generated a one-time password (OTP). Within seconds, Treasury records show the same OTP applied to authorize a command. Meanwhile, internal messaging logs indicate normal activity by employees elsewhere, including Jayasurya, who committed a code change at nearly the same time.

By 12:12 AM, Kanishka was logged entering the CFO’s office carrying a small package. Minutes later, Treasury systems detected the mounting of a USB device under the alias /mnt/cakebox.

At 12:15 AM, the Treasury badge system shows Thejas swiping into the secured wing. CCTV, however, places him in the lobby. Concurrently, a repository commit attributed to Abbilash appeared corrupted upon inspection.

At 12:17 AM, several Treasury logs were deleted. Surviving fragments read:
12:15:44 AUTH SUCCESS  
12:15:45 USB mount detected  
12:15:46 INITIATING TRANSFER: 50,00,00,000.00

At 12:20 AM, an internal email confirming that the transfer had been completed was circulated under Rizvi’s name. The digital signature was valid, but the origin traced back to an internal test server operated by Darshan.

By 06:00 AM, Treasury staff discovered that ₹50 Crores were missing. Physical inspection revealed no signs of forced entry.

## Status ##
The event remains under classification as a coordinated insider operation. Further analysis is ongoing. Cross-referencing across departments and systems will be required before establishing accountability.
Supporting files in this repository:
timeline.txt – official chronological record 
metadata.json – flagged technical anomalies
