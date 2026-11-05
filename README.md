# Align 0.9 Preview — individual back muscles

[Download Align 0.9.0 Preview APK ZIP](https://github.com/pristen01/apk/actions/runs/42109585213/artifacts/13453725584). Sign into GitHub, extract the ZIP and open Align-0.9.0-preview.apk.

Export your current Preview data first. Each Actions run currently uses a new preview signing certificate, so Android may require uninstalling the previous Preview. Keep the original Align app; it is separate.

## Individual back anatomy

The atlas now retains separately named source meshes for upper/middle/lower trapezius, latissimus dorsi, rhomboid major/minor, posterior deltoid, infraspinatus, teres major/minor, longissimus, iliocostalis, multifidus, spinalis and quadratus lumborum. These are source anatomical structures, not regions guessed from screen coordinates.

Home → Explore back muscles opens the named picker and rotates to the back. Tap a visible muscle or choose its name to see its role and relevant exercise guides. Expose deep back filters out superficial muscles while retaining skeletal context. Muscle taps take priority over context bones in atlas mode. Each muscle page explains that exercises recruit multiple muscles rather than isolating activation perfectly.

The library now has 30 guides. Six additions cover gentle shoulder shrugs, Y raises, pulldown technique, rear-delt fly technique, external rotation and supported scapular retraction. Example doses remain editable, and the app does not prescribe heavy loading from anatomical appearance.

Back & Nerve Care, camera checks, regional browsing, planning, workout logging and journals remain available.

## Validation and limits

40 local checks passed, including individual-mesh presence, muscle-to-exercise routes, distinct trapezius selections, legacy highlight aliases, pose geometry and symptom gates. The GitHub workflow rebuilt the atlas, compiled the APK and verified signing successfully. Physical-phone interaction and new motion appearance remain unverified. Posing is approximate educational illustration, not a clinical form assessment or an activation/nerve-tension measurement.

## Sources and build

The workflow rebuilds attributed Z-Anatomy / BodyParts3D meshes from pinned public source revision `8ca3b7421bcfbe88b85859eb1983d5cf79f21749`, using the bundled preparation script. Meshes and adaptations retain CC BY-SA notices. Three.js is MIT; Draco is Apache-2.0.

Muscle actions are summarized from OpenStax anatomy; AAOS shoulder conditioning informs relevant technique. Both are linked inside the guides. Neither endorses this app. The screenshot served as a visual requirement; its image is not redistributed.

Actions → Build Align Preview APK → Run workflow. Artifacts last 30 days. No user data or private signing key is included in the source overlay.
