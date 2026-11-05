# Align 0.7.1 Preview — anatomy, movement and care

[Download the latest APK ZIP](https://github.com/pristen01/apk/actions/runs/42104419218/artifacts/13451975403) while signed into GitHub. Extract the ZIP and install Align-0.7.1-preview.apk.

Export any data in an earlier Align Preview before uninstalling it. Each Actions build currently generates a new preview signing certificate, so Android may require removing the prior Preview. The original Align app is separate and should be kept.

## Layout reference applied in 0.7.1

The user video identified [DuarteSantos8/openGym](https://github.com/DuarteSantos8/openGym). Its Home, Plan and Workout views informed an original Monday-first weekly strip, day-filtered routines and a quieter workout screen with secondary exercise actions under More. Schedule dots represent actual local routines/logged workouts. No openGym source code or assets were copied. The interactive Align anatomy remains central.

34 automated tests passed, including new local-date/week-boundary tests. GitHub build and signing verification passed; physical-phone layout remains unverified.

## Design changes in 0.7

A graphite design with teal, iris and champagne accents; anatomy-first hierarchy, expandable viewing tools, five-item bottom navigation with vector icons, revised focus selection, exercise cards, training cards, calendar, Care pages and dialogs. Text and controls use a consistent spacing and contrast system. Camera scanning remains available from the Body screen. Reduced-motion preferences are respected. The openGym reference is now identified and its relevant layout structure has been reviewed.

Build and signature checks passed; 32 automated tests and document/style checks passed. Live phone appearance remains unverified.

## Features from 0.6

- Upper back and lower back are separate selectable areas. Forearm muscle geometry is separated at runtime from the bundled merged muscle group for regional selection/highlighting. Quads, hamstrings and calves remain individually accessible.
- 24 built-in guides: eight additions cover forearm movement, heel slides, glute activation, shoulder-blade setting, band-row technique, supported hip abduction and seated calf work. New cards open the animated guide rather than showing an unrelated movement thumbnail.
- Dedicated Care section: sciatica flare-up guidance, sitting and sleep-position anatomy, home/bodyweight and supported-strength options, a clinician-gated nerve slider, plus separate hip-control and pelvic-movement guides.
- Teal, blue and warm accents distinguish anatomy, care and training; stronger cards and larger controls improve visual hierarchy.

Care links to NHS sciatica information, NHS Wales sleeping guidance and South Tees sciatica facts. These are original educational summaries, not personal prescriptions or promises to release nerve compression. Pelvic tilt and visible asymmetry do not diagnose the source of pain.

32 automated checks pass. The GitHub Actions build compiled and verified the APK signature. Physical-phone behavior and the new educational poses have not been clinically validated; use written technique and individualized advice. Existing rotatable anatomy, camera scanner, routines, logging, imports/exports and journals are retained.

## Build again

Actions → Build Align Preview APK → Run workflow. The workflow restores verified base assets and overlays embedded source. Artifacts are retained 30 days. It includes no private signing key or user data.

Anatomy derives from Z-Anatomy / BodyParts3D under CC BY-SA. Attribution and original clinical source links are bundled. Three.js is MIT; Draco is Apache-2.0. Runtime regional grouping is an approximate display adaptation. New card previews label anatomy/guide availability rather than claiming a photographed demonstration.
