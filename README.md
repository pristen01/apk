# Align — anatomy and training

## Align 0.5 Preview via GitHub Actions

[Open the build](https://github.com/pristen01/apk/actions/runs/42022712835) or [all builds](https://github.com/pristen01/apk/actions).

The initial build succeeded. To download it, open its summary and download **Align-0.5.0-preview** under **Artifacts**. Sign in to GitHub to download the ZIP. Extract it and open `Align-0.5.0-preview.apk` on your Android phone.

The app is named **Align Preview** and installs alongside Align 0.4. It has a separate local journal; it does not migrate or delete your existing app data. Each workflow run uses a fresh preview signing key. A future preview build may require uninstalling the previous preview; export its data first. The original app is unaffected.

To build again, go to Actions → Build Align 0.5 Preview APK → Run workflow. Artifacts are retained for 30 days.

### What's included

- Selectable 3D anatomy with muscle, bone, nerve and logged-muscle-coverage views.
- 16 built-in illustrated exercise guides, plus custom exercise logging.
- Dark training layout, library search and favorites.
- Editable routine builder, workout drafts, sets, reps, load units, optional RIR and rest timers.
- Workout calendar, recorded-load history and summary sharing.
- CSV import/export, training JSON backups and manual food/weight journals.

32 local automated checks passed before this workflow was added. The workflow compiles and verifies the APK signature. Successful compilation is not proof of physical-phone compatibility; phone interaction and camera behavior still require device testing.

Exercise guidance remains educational, not a diagnosis or personalized rehabilitation prescription. Muscle coverage describes logged target sets, not measured recovery or weakness. Original clinical references and atlas license notices remain bundled.

### Build source and licenses

The self-contained workflow restores verified assets from the existing Align 0.4 APK and overlays the 0.5 text source embedded in its base64 ZIP. It includes no private signing key or user data. The source ZIP can be decoded locally for inspection. Anatomical assets derive from Z-Anatomy / BodyParts3D under CC BY-SA; Three.js is MIT and Draco is Apache-2.0. Original notices are bundled in the APK.

[Existing Align 0.4 APK](https://github.com/pristen01/apk/raw/refs/heads/main/Align-0.4.0.apk) · [0.4 adapted anatomy source and notices](https://github.com/pristen01/apk/raw/refs/heads/main/Align-0.4.0-anatomy-source.zip)
