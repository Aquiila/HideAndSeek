# Jetlag hide and seek requirements

First version of a mobile app for playing a hide and seek game inspired by the Jet Lag YouTube channel. This is a fan-made game with an original question deck. It does not copy the show's cards or wording.

## Players

- One phone per team. Two teams: hiders and seekers.
- More than one phone on a team is a later idea, not part of the first version.
- Only the people playing. No spectators.

## Platform

- Android first.
- iPhone later.

## Before the game

- One phone sets up the match. The other team joins with a code.
- No account. Game sizes and their parameters are saved on the phone.
- Creating a match starts by choosing a size: small, medium, or large.
- Each size has its own parameters, including the game clock and the question timer. The phone ships with defaults. The player can change them in settings, and those changes stay on that phone.
- The size chosen for a match, and the parameters it had at that moment, travel with the match. The other phone uses those, not its own saved settings.
- The host sets the play border and the places that are in play.
- In-play places are usually a circle around a transit station. Default radius is 250 meters. Choices include 100, 250, and 500 meters, plus a way to fine-tune.
- On the phone, the map moves under a fixed crosshair. The player does not drag a tiny pin.
- Chosen stations also appear in a list, because small circles are hard to tap.

## During the game

- The app knows both teams' GPS positions.
- Hiders see the seekers on the map. Seekers never see the hiders.
- Everyone plays fair. For a radius or distance question, the app calculates the answer from GPS and the hider cannot change it.
- GPS can be off by tens of meters. How a close call is decided is still open. The hider still cannot override the result.
- The hider chooses only when to send that answer, and can choose not to send it.
- A question has a visible countdown for the hider. Missing the deadline has no penalty yet.
- One question at a time. Seekers ask. Hiders see the true calculated answer, the countdown, and then send or hold.
- First questions: "Inside this distance?" and "Closer to this station than we are?"

## Where the hider can be

- Each sent answer changes the area where the hider can still be. Both phones show that area.
- Yes to "within 2 km of us" keeps only the inside of that circle. No keeps everything outside it. The play border still limits the map.
- Places the hider cannot be are greyed out. The remaining area stays clear.
- A held or unsent answer does not change the area. Only a sent answer does.
- The map has two views. The live view is the game as it stands after sent answers. The plan view lets a seeker try a question and see how yes and no would change the area, without asking it yet. The hider can open the same plan view.

## Endgame

- Endgame starts when a seeker enters the station area where the hider is.
- Only the hider is told. The seeker is not.
- The hider gets a notification and a small marker on the map that stays while endgame is on.

## Honesty, proof, and cards

- Honesty is an agreement between the teams. The app does not judge it.
- Either team can send photos and short videos to the other, on a question or on their own.
- A photo or video is optional. An answer does not need one, unless the question itself asks for a picture. When someone sends one, it is evidence for the people.
- A question that asks for a picture opens the camera prompt with the answer. Other questions leave the camera out of the way.
- Before a photo is sent, the hider sees a preview. They can crop it, retake it, or send it.
- Cards stay a physical deck. After an answer is sent, the app reminds the hider to draw a card. No digital deck in the first version.
- A custom digital deck can come later.

## How a round ends

- The hider taps Found.
- The game clock is the backup: time's up also ends the round. Its length comes from the chosen game size.
- Being near the hiders never ends the round. Seekers can stand close and still not see them, so distance is not a win, in this version or later.
- Leaving the border warns and keeps tracking. A Found tap from outside the border is blocked.

## Not in the first version

- Several phones on one team.
- iPhone.
- Spectators.
- Digital or custom cards.
- A penalty for a missed answer deadline.
- Drawing the border by hand as a polygon.
- Ending a round from GPS distance.

## Still to confirm

- Exact warning when someone leaves the border.
- The default game clock and question timer for small, medium, and large.
- How large a photo or video can be.
- What the seeker sees while waiting for an answer.
