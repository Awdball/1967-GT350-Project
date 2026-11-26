# 1967 Shelby GT350 Build — Project Memory

This file is automatically loaded by Antigravity at the start of every conversation in this workspace to maintain persistent context about the build, intent, and parts compatibility.

## Assistant Instructions
1. **Read `PARTS_LIST.md` first** before recommending new parts, so suggestions match existing selections, clearances, finishes, and fuel/ignition architecture.
2. **Update `PARTS_LIST.md`** whenever a part is selected, purchased, shortlisted, or ruled out, including exact part numbers, key specs, and rationale.
3. **Verify compatibility** across systems (e.g., carburetor flange/linkage vs. intake & transmission kickdown, hood/air-cleaner clearance, fuel delivery & AN fittings, electrical load).
4. **Sync to GitHub** (`origin`) when changes are finalized and the user asks to commit/push (or remind the user if git credentials are needed).

---

## Build Configuration & Intent
*(Fill in or update these details as decisions are finalized.)*

- **Vehicle:** 1967 Shelby GT350 (Restomod)
- **Primary Use / Intent:** Street & Autocross / Road Course
- **Core Philosophy:** Maximum flexibility — ability to revert to a 100% mechanical setup with minimal work in a SHTF scenario; diagnosable and serviceable by a shade-tree mechanic.
- **Aesthetic / Finish Direction:** **Ford Antimatter Blue** exterior; period-correct GT350 / Cobra look or clean restomod (keeping 302-deck 363ci for authentic GT350 proportions)
- **Engine:** FordStrokers 363 Liberator (Dart SHP block, 4.125" x 3.400", **Internally Balanced 0 oz**, ~10.2:1 CR) — see [`ENGINE_SPEC.md`](./ENGINE_SPEC.md) & [`build_data.json`](./build_data.json)
  - **Heads / Intake:** AFR 195 Competition `#1381` (58cc, angle-plug, +0.125" raised exhaust ports, 7/16" studs, Trick Flow 1.6 rockers) / Edelbrock RPM Air-Gap `#7521` (4150 flange, 4.90" pad height)
  - **Camshaft / Idle Vacuum:** COMP Cams Custom Billet Hyd Roller `#35-000-9` ("FIEGENER"): `226°/234° @ .050"`, `.563"/.566"` lift, `110°` LSA, `106°` ICL, `1-3-7-2-6-5-4-8` firing order *(requires melonized/steel/composite distributor gear)*
  - **Oil Pan:** Moroso `#20535` (7qt front-sump road-race baffled, 8.0" deep, passenger kickout, pan-mounted dipstick; no Mustang II IFS)
  - **Timing Cover / Fuel Drive:** Fox Body timing cover, **NO fuel pump eccentric installed** *(if using Holley Mid-Mount w/ mechanical fuel pump + PS, must add eccentric, grind timing cover clearance wall, and add Holley `97-436` PS relocation + remote reservoir)*
  - **Valve Covers (Acquired):** Ford "Cobra" solid block-lettered cast aluminum *(verify clearance over Trick Flow 1.6 roller rockers)*
  - **Compression Ratio:** 10.2:1
- **Fuel Type & Tank:** Gasoline (91–93 pump gas); **MTF Side-Fill Tank + Sail-Panel Radium Engineering Filler Neck (Acquired)** *(piping/hose to tank still needed)*
- **Exhaust (Acquired):** **FPA (Stan) Custom Ceramic-Coated Headers** — built specifically for `363` + `AFR 195` + manual trans + `UNI-8010830-01` Unisteer rack + `IDI-1120643051` IDIDIT column
- **Accessory Drive (Shortlisted):** **Holley Mid-Mount SBF** *(has mechanical fuel pump boss; requires `97-436` PS relocation + remote reservoir to run mech pump + PS together, plus 0 oz damper spacer check & 1,100 PSI low-flow PS valving)*
- **Cooling (Needed):** Aluminum radiator + staged dual SPAL puller fans & shroud *(verify 20" vs 24" '67 core support & pulley-to-core depth)*
- **Chassis / Suspension (Acquired — Street or Track):** `SOT-PACKAGE1` Front & Rear Coilover System (`SOT-3LINK-U-BRACKET-FIXTURE` 3-link rear), `SOT-BBSPINDLE` Drop Spindles, `SCD-C7ZZ-5482-B` 1-1/8" Front Sway Bar, `SOT-EXPORT` Billet Export Brace, `SOT-QRSTB` Quick-Release Monte Carlo Bar
- **Steering (Acquired):** `UNI-8010830-01` Unisteer Power Rack & Pinion (Late '67–70; requires **1,100 PSI low-flow** PS pump, `17mm DD` pinion), `SOT-DROPTIERODS`, `IDI-1120643051` IDIDIT Tilt Column
- **Brakes (Acquired — Street or Track / Wilwood):** Front `SOT-13X125-2PC-4P-ALUM-LEADING` (13"×1.25" 4-piston — **17"+ wheels required**), Rear `ST-12BKR-T` (12"×.810" — **Torino 9" axle bearing ends required**), `WIL-261-15544-BK` Manual 1" Bore Tandem M/C w/ Prop Valve
- **Transmission:** **Planned:** **Modern Driveline Tremec TKX Swap Kit** (must specify **0 oz neutral-balance** flywheel). *(Currently have loose 4-speed Toploader, unknown gearset, no bellhousing).*
- **Rear Axle / Gear Ratio:** **Quick Performance 1964–66 Mustang 9" Housing & Axles (Acquired)** — `2"` narrower than '67 for deeper wheel lip w/ **Mustangs to Fear mini-tubs** (moved to frame rails); Fabricated Big Web, `1/4"` heavy-wall tubes (for 3-link welding), **Torino 3/8" ends** (matches `ST-12BKR-T`), **31-spline**, `5x4.5`, `1/2"-20 x 3"` studs. **Third Member (Acquired):** **Eaton Detroit Truetrac 31-Spline, 3.70 Gear** (`B01M6Z8SYZ` — helical gear LSD, no clutches, **1350 Billet Yoke & U-bolts**).
- **Wheels (Planned):** Custom 3-piece **Augment Wheel Company** (`17"+`, `5x4.5`, open-ended lugs; pending remote car measurements & SOT brake template check)
- **Interior / Safety (Acquired):** Mustangs to Fear Shelby-style roll bar; refurbished factory seats
- **Ignition / Electrical:** *(TBD — must support 100% mechanical fallback / shade-tree serviceability; 100A+ alternator recommended for dual SPAL fans)*
- **Known Constraints:**
  - **0 oz neutral balance** damper and flywheel/flexplate required.
  - **1,100 PSI low-flow** power steering pump required for `UNI-8010830-01` Unisteer rack (match to Fox timing cover / front accessory drive).
  - **17"+ wheels** required to clear `SOT-13X125-2PC-4P-ALUM-LEADING` 13" front brakes (check SOT fitment template).
  - **Torino bearing ends** required on 9" rear axle for `ST-12BKR-T` rear brakes.
  - **1967 Shelby hood & Monte Carlo bar clearance** with `4.90"` Edelbrock 7521 Air-Gap intake.
  - **Header/plug/steering/pan clearance** with AFR 195 raised exhaust ports, angle plugs, `8.0"` deep front-sump Moroso `#20535` pan, and Unisteer rack + IDIDIT column shaft.
