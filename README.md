# ROCKPAPERSCISSORS!

This version of the classic chance-based game has been rebuilt into a colourful, responsive web page with four visual themes, sound effects and a small modal that appears at the end of each game. The interaction is simple: pick rock, paper or scissors; get a (randomly-selected) response from the computer, and the result appears instantly.
The design is intentionally bold and bright, with soft edges, large imagery and a layout that stays stable across screen sizes.

<img src="README%20images/main-image.jpg">
<br><br>
The live game can be viewed here: <a href="https://jillusc.github.io/ROCKPAPERSCISSORS-rebuild/">ROCKPAPERSCISSORS!</a>

## Functionality

The game follows the familiar rules: rock beats scissors, scissors beats paper, paper beats rock. The player selects one of the three options using illustrated buttons. A short delay is used before the computer reveals its choice, and the central play area displays both images side by side.
Scores are shown in a bar underneath. The game ends when either side first reaches five wins. At that moment, a styled modal appears announcing the result, and includes a restart button. Confetti is triggered for a player win.

## Features

### Responsive layout

The page has been rebuilt using a clearer grid and flex structure so it stays centred and balanced at widths from mobile up to large desktop screens. The layout moves to a two-column design at tablet size and above.

### Design

- the colour scheme utilises a neutral grey background with highly contrasting 'juicy' colours for the gaming area features, intended to draw the eye and encourage the user's desire to interact
- the font, Sigmar, is imported to the CSS from Google Fonts; it is chunky with soft edges and an air of fun
- the title is written in capital letters without spaces and has an exclamation mark at the end: this is to reinforce the idea that this game is customarily fast whilst players say out loud the words, "Rock, paper, scissors!" before immediately revealing their choice in a quick hand motion
- the logo image was created using Photoshop and features a juxtaposition of the three images used for each choice in the game; these are photographic and therefore present an interesting visual when, possibly, a graphic may be expected. This, again, is intentionally avoidant of childlike associations whilst simultaneously also not being a barrier to younger players
- the player buttons were also created using Photoshop and utilise the same images; they are round buttons to support the presentation of chunky visuals and a fun vibe
- the gaming areas have borders with rounded corners for a cartoon-like aesthetic and visual appeal
- the simplistic design of the header allows the emphasis to fall on the colourful gaming area
- contrastingly, the footer is a simple band of colour to signify the bounds of the viewing area
- the favicon was created using Photoshop: it complies with the overall theme by being simple, round like a button and comprised of the main three colours.

### Colour themes

A set of four theme dots lets the page shift between Classic, Retro, Neon and Monochrome colour schemes. Each one applies its own palette through CSS custom properties, and can be switched during play.

### Sound effects

A fun sound accompanies each choice of rock, paper and scissors, and a short phrase is played at the end of the game, depending on whether the player has won or lost. A small speaker icon in the header allows the user to control muting and unmuting sounds at any time.

### Subtle animations

Buttons grow slightly on hover, the mute button scales up gently, and confetti animates at game end.

### End-game modal

Instead of using a browser alert, the page now shows a custom modal containing the win or loss message, a restart button and confetti for the winning scenario.

<img src="README%20images/game-end-modal.jpg">

## Testing

The page was tested in Chrome, Firefox, Edge and Safari browsers.
All core interactions work as expected: the buttons register correctly, the computer's choice is generated after the short delay, and scores update accurately.
The four themes apply consistently, and the mute button prevents audio playback as intended.
The end-game modal displays reliably and the restart button resets the scores.
The layout was checked at a variety of widths to confirm that the grid shift, margins and centring behave predictably.
HTML and CSS pass W3C validation.
Lighthouse was used to assess accessibility.

## Deployment

The site is deployed using GitHub Pages:

- Settings → Pages → Deploy from branch → main → root folder.

## Credits

Images were sourced from free image sites as detailed below:

- rock - <https://clipart-library.com/clip-art/rock-clipart-transparent-20.htm>
- paper - <https://www.pngwing.com/en/free-png-icbtr>
- scissors - <https://clipart-library.com/clipart/883558.htm>

Confetti animation uses the lightweight canvas-confetti library.
