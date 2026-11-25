# Hide and seek requirements

First version of an Android app for two teams, one phone each. It is a fan-made game inspired by Jet Lag, with an original question deck. It does not copy the show's cards or wording.

## Players

- Two teams: hiders and seekers. Only the people playing. No spectators.
- Several phones on one team, iPhone, spectators, and a separate chat are later.

## No account

- Nothing is stored in an account. Sizes and their settings are saved on the phone.
- A match starts by choosing small, medium, or large. The host can change that size's settings, and the phone remembers them for the next match they host.
- The size and settings chosen for a match travel with the match. The other phone uses those, not its own saved settings.
- The other team joins with a code, or by scanning a QR code when the phones are nearby.

## Setup

The host does this in three steps.

1. Search a city. The app uses that city's boundary as the play border. The host confirms it on the map. Combining cities into one metropolitan border is later. Drawing the border by hand is not planned.
2. The app lists transit stations inside that border, grouped by mode: metro, train, bus, tram, and ferry. Metro and train start on. Bus starts off. Grouping by transit line is later.
3. The host can turn a whole group off, remove one station, or add a station the search missed. Adding a station uses a fixed crosshair: the map moves under it.

Each chosen station is a possible hiding zone. The circle is 250 meters for small, 500 meters for medium, and 1 kilometer for large. The same list can be opened from a toggle.

## Hiding period

- A round starts with a countdown both teams can see. Small is 30 minutes, medium is 60, large is 180. Both teams get an alert when it ends.
- Seeking starts the moment hiding ends. There is no Start seeking button. The seeker phone notifies them that it is their turn to move. Ask stays locked until then. The hider is alerted too.
- The hider does not pick a station. When the countdown ends, the zone is the marked station nearest the hider. The center is the station.
- Seekers can see every possible zone. They never see which one was chosen.
- The in-game bar has two clocks. The left clock is the hiding countdown. The right clock is a seeking stopwatch. The stopwatch is not a countdown and not a time limit.
- During hiding the countdown runs and the stopwatch stays grey at 0:00. After hiding, the stopwatch counts up and the hiding clock is grey at 0:00.
- The stopwatch stops when the hider taps Found. That elapsed time is how long the seekers took.

## Questions

One question at a time. Seekers ask. The hider sees the answer and a countdown, then sends it. There is no Hold button. Not sending is the hold. The map stays as it is until the hider taps Send. Ask stays locked until seeking starts.

Questions open as one bottom sheet over the map, about half height, with the map still visible. It opens on category icons. Tapping a category replaces the sheet with that category's question list. A back chevron labeled Questions returns to the icons. The phone Back does the same. The app does not stack a second sheet. Drag the sheet down to see the map. In the first version only Radar is active. Matching, measuring, thermometer, and photos stay visible but inactive.

The app calculates matching, measuring, thermometer, and radar from GPS. The hider cannot change those answers. GPS can be off by tens of meters, and how a close call is decided is still open. Photos are taken by the hider.

| Category | Question | Time | Cards |
| --- | --- | --- | --- |
| Matching | Same nearest place, or same administrative division? | 5 min | Draw 3, keep 1 |
| Measuring | Closer to or farther from this place than we are? | 5 min | Draw 3, keep 1 |
| Thermometer | After we travel at least this far, hotter or colder? | 5 min | Draw 2, keep 1 |
| Radar | Within this distance of us? | 5 min | Draw 2, keep 1 |
| Photos | Send a photo of this. | 10 min small and medium, 20 min large | Draw 1 |

Tentacles are later.

Each category is a list. A question that has been asked is greyed out on both phones. In the first version that happens once. Later, the shade can deepen on each repeat, and the card reminder can ask for a larger draw.

If the countdown runs out before the answer is sent, the hider's hiding clock pauses until they send it, and the app reminds them that this answer draws no card.

Cards are a physical deck. After an on-time answer, the app reminds the hider how many cards to draw and keep. A digital deck is later.

## The possible area

- Only a sent answer changes the area where the hider can still be. Both phones show it. A held answer changes nothing. There is no Hold button. Not sending is the hold. The map stays as it is until the hider taps Send.
- Yes to "within this distance" keeps the inside of that circle. No greys out that circle. The play border still limits the map.
- Places the hider cannot be are grey. The rest stays clear.
- Live view shows sent answers. Plan view lets either team try a question and see yes and no before it is asked. Plan view stays out of the first version. The map still changes only after a sent answer.

## Photos and video

- Either team can send a photo or a short video with a question or on its own. A photo is evidence for the people. The app does not judge honesty.
- An answer needs a photo only when the question asks for one. That question opens the camera. Other questions leave it out of the way.
- Before a photo is sent, the hider can preview it, crop it, or retake it.
- How large a photo or video can be is still open.

## Endgame, rounds, and scoring

- Endgame starts when a seeker enters the hider's zone. The app does not guess whether the seeker is on transit.
- Only the hider is told, with a notification and a marker that stays on their map.
- Teams switch hiding for as many rounds as they want. The app keeps each team's longest hiding time and shows both. The longer time wins.
- Game settings can end a round after a chosen time, end the whole game after a chosen time, or both. Either limit can be left off. Those limits are separate from the seeking stopwatch.
- The hider can end a round early with Found. That tap stops the seeking stopwatch. The elapsed time is how long the seekers took.
- Standing near the hiders never ends a round.
- Leaving the border warns and keeps tracking. The exact warning is still open.

## Still open

- How a close GPS call is decided. The hider still cannot override it.
- The exact warning when someone leaves the border.
- How large a photo or video can be.
- What the seeker sees while waiting for an answer.
