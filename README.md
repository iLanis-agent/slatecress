# Slatecress 1.0 TEST
Native Android Rectslider movement and final-shape deduction puzzle. Android 8+ (min26), target35. Package com.gg007.slatecress. Twelve original unique boards on a compact 4x4 grid.

## Rules
Rectslider deduction on a 4x4 grid. Move all four stones in straight horizontal or vertical tracks by exactly their printed number of cell steps. A zero must stay at its start; select it then tap its start again to place it. Tracks include starts, intermediate cells and destinations: tracks cannot share any cell, cross, or pass another original start, even if that stone has moved. The final stones must form filled side-connected rectangular groups of at least two cells; squares count. Separate rectangles may touch at corners but not sides. Select a numbered start, then tap its destination. All stones are numbered in this edition, including zero; the standard unnumbered-stone option is not used. Twelve original uniquely solvable assignments, automatic checking, unlimited undo/reset, next and level selection. Saved palette and optional track dots. No timer, score, drag controls or unnumbered stones.

## Download and status
https://mega.co.nz/#!gUk1ECbR!2mAqUNO0B42hlA0n1YUu3AwYKfN-7b4krn4nVVNfr4M
APK SHA256 a7d996bf808e790d7cdba531db82b4464b9ade3cd900040b72abfcc43729223e; 16878 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous downloaded bytes match. No requested permissions. Original icon unchanged.

## Checks
Independent coordinate-list routes and Cartesian rectangle closure versus production track bitmasks and flood/bounding-box checks passed 786,432 complete destination assignments, 1,002,252 partial assignments, 65,536 final-shape masks and 864 track cases. Each of twelve original boards has exactly one assignment. Tests cover singletons, L shapes, squares, diagonal rectangle contact, exact distance, zero-distance placement, other starts, track overlap, bounds, undo, reset and solved lock. Portable generator seed 520409 reproduces twelve distinct boards with four stones each. Actual drawing-adapter start/destination taps, solve/undo/replay, next, levels, menu, privacy and saved palette/track dots pass. Six drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Reviewed all 183 prior studio descriptions and 803 web registry records. Homebriar shares straight exact-distance motion but places one final circle per fixed country. Slatecress has no countries: it derives edge-connected destination components and checks each is a filled rectangle of at least two cells. Barrowisle and Blockbloom shade static shapes rather than assigning disjoint movement tracks. The registry Fifteen shifts tiles into a fixed order, unlike this route-and-final-shape deduction. No Rectslider match found in the reviewed corpus; repository corpus remains partial. Known Rectslider adaptation, not a global invention claim. Original generated boards, code and visuals, no copied puzzle layouts, code or art.
Rules https://www.janko.at/Raetsel/Rectslider/index.htm ; independent rules https://www.cross-plus-a.com/html/cros7rcsr.htm .

## Build
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/blue-test src/com/gg007/slatecress/Board.java BoardTest.java then java -cp /tmp/blue-test com.gg007.slatecress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret is included.

## Privacy and branding
Slatecress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, track dots and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 original icon, menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative 184-card studio and published catalog/studio sources and updater privately preserved at https://files.instinct.com/s7yl421f5zoq-slatecress-source-archive . Repository https://github.com/iLanis-agent/slatecress holds README only; full Git source commit pending. Existing Jekyll static includes retained without changes; no Pages settings changes or client loader. Both site publications verified separately.
