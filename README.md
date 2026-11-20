# Bullpen Baseline

A browser application for pitching video review, bullpen logging, mechanics measurements, and coach planning.

## Run

Open index.html in Chrome or Edge. Internet access is required for the MediaPipe tracking runtime and model downloads. Videos are processed locally. Saved sessions and clips use browser storage on the current device.

## Workflow

1. Enter the pitcher profile and name the session.
2. Load one pitch per clip and select the camera view and throwing hand.
3. Mark delivery events and run analysis.
4. Enter pitch outcomes and optional radar measurements.
5. Review the comparisons, record one cue to test, and save the session.

JSON and CSV exports contain measurements and notes. JSON does not contain video files. Clearing browser data can remove saved sessions and videos.

## Current scope

Mechanics measurements are camera projections and depend on visibility and manual event markers. Personalized ranges use comparable pitches logged in the session. The application does not yet include a validated professional reference library. Live footage validation and browser testing remain pending.

Training suggestions are general coaching options. Youth game rest guidance is linked to MLB Pitch Smart. Reported throwing pain routes the pitcher toward medical evaluation.

## License

See LICENSE.

