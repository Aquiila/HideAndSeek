# Hide and seek user stories

Inside each section, stories are ordered high, then medium, then low. High is the first playable version. The full rules stay in the requirements.

The first version is two phones, one hardcoded city and its stations, and no photos or video. Players use another app for pictures. Only Radar is active. Matching, measuring, thermometer, and photos stay visible but inactive.

## Set up a match

### High

As a host, I want to start a match without an account, so that we can play as soon as both phones are together.

As the other team, I want to join with a code, so that I enter the same match.

As a host, I want the stations to be the possible hiding zones, so that the hider's zone will be one of them. Seekers can see every zone and never see which one was chosen. The first version uses a hardcoded list.

### Medium

As a host, I want to pick small, medium, or large, so that the match uses that size's settings. The first version uses one hardcoded size.

As the joining team, I want this match to use the host's size and settings, so that my own saved settings do not change it. The first version has one shared hardcoded setup.

As the other team, I want to join by scanning a QR code, so that joining is easier when we are nearby.

### Low

As a player, I want my changes to those settings saved on my phone, so that the next match I host starts from them.

As a host, I want to search a city and use its boundary as the play border, so that I do not draw the border. The first version uses one hardcoded city.

As a host, I want stations inside that border grouped by mode, so that I can turn a whole group on or off.

As a host, I want to remove one station or add one the search missed, so that I can correct the list.

As a host, I want to place an added station by moving the map under a crosshair, so that my finger does not hide the point.

As a host, I want the station list behind a toggle, so that I can open it.

## Hiding period

### High

As either team, I want a hiding countdown from the start, and an alert when it ends, so that we both know when seeking begins. Seeking starts the moment hiding ends. There is no Start seeking button. The seeker phone notifies them that it is their turn to move. Ask stays locked until then. The hider is alerted too.

As a hider, I want the app to choose the nearest marked station when that countdown ends, so that I do not pick one myself.

As either team, I want two clocks on the in-game bar, so that hiding time and seeking time stay distinct. The left clock is the hiding countdown. The right clock is a seeking stopwatch, not a countdown and not a time limit. During hiding the countdown runs and the stopwatch stays grey at 0:00. After hiding, the stopwatch counts up and the hiding clock is grey at 0:00. The stopwatch stops when the hider taps Found. That elapsed time is how long the seekers took.

## Play the map

### High

As a hider, I want to see the seekers, so that I know where they are.

As a seeker, I want the hiders hidden, so that I have to find them.

As either team, I want the app to know both positions, so that it can calculate radar answers and notice endgame.

### Low

As a hider, I want a warning if someone leaves the border, with tracking still on, so that leaving does not silently end the game.

## Questions

### High

As a seeker, I want to ask one radar question at a time, so that we are never answering two at once. Ask stays locked until seeking starts.

As a seeker, I want questions in one bottom sheet over the map, about half height, so that the map stays visible. It opens on category icons. Tapping a category replaces the sheet with that category's question list. A back chevron labeled Questions returns to the icons. The phone Back does the same. The app does not stack a second sheet. Drag the sheet down to see the map. In the first version only Radar is active. Matching, measuring, thermometer, and photos stay visible but inactive.

As a hider, I want to see the calculated radar answer and its countdown, so that I know the result and how long I have.

As a hider, I want that answer locked, so that I cannot change it.

As a hider, I want to send the answer when I choose, so that I decide when the seekers learn it. There is no Hold button. Not sending is the hold. The map stays as it is until I tap Send.

### Medium

As a hider, I want my hiding clock to pause if the countdown runs out, and a reminder that this answer draws no card, so that the delay is not hiding time.

As a hider, I want a reminder of how many physical cards to draw and keep after an on-time answer, so that the deck stays in our hands.

As either team, I want an asked question greyed out in its list, so that we can see it was used.

### Low

As a seeker, I want matching, measuring, thermometer, and photo questions, so that we can ask more than radar. In the first version those categories stay visible but inactive.

## The possible area

### High

As either team, I want a sent radar answer to update the shared area, so that we see the same search. The map still changes only after a sent answer.

As either team, I want a yes to keep the inside of the circle and a no to grey it out, so that the map matches the answer.

As either team, I want an unsent answer to leave the map unchanged, so that silence is not treated as a fact. There is no Hold button. Not sending is the hold. The map stays as it is until the hider taps Send.

### Medium

As either team, I want a plan view of yes and no before a question is asked, so that planning stays separate from the live map. Plan view stays out of the first version.

## Photos and video

### Low

As either team, I want to send a photo or a short video, so that we can show what we see. Another app can do this for now.

As a hider, I want a photo question to open the camera, with a preview to crop or retake.

## Endgame and scoring

### High

As a hider, I want a notification and a marker when a seeker enters my zone, so that I know endgame has started.

As a seeker, I want no sign that endgame started, so that I do not learn I am in the right zone.

As a hider, I want to end a round with Found, so that we stop when the seekers see us. That tap stops the seeking stopwatch. The elapsed time is how long the seekers took. The stopwatch is not a time limit.

As a seeker, I want standing nearby to never count as a win, so that we have to actually see each other.

### Medium

As either team, I want to switch who hides for as many rounds as we want, so that each team can try again. The first version can be one round, then a manual switch.

As either team, I want each team's longest hiding time shown, so that the longer time is the winner.

### Low

As a host, I want optional time limits for a round and for the whole game, so that we can stop on a schedule.

## Later

Several phones on one team, iPhone, spectators, a separate chat, a digital deck, combining cities, grouping stations by line, tentacle questions, and a deeper shade plus a larger card draw when a question is asked again.
