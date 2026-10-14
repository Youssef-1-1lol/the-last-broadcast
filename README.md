# The Last Broadcast
CCT360 Interactive Discovery. A fictional mystery set in North Point radio station.

## Run
Open index.html directly, or serve this folder with any static web server. All image and sound files are included. No API keys, packages, external fonts, analytics, or backend are required.

## Experience
Six scenes: arrival, station map, listening room, archive, rooftop relay, broadcast desk. The listening room, archive, and relay can be explored in any order. Hash links support browser back/forward. The final desk unlocks after three evidence items. Two editorial choices produce different endings.

## Interactions
- Choose locations from a map
- Tune to 88.4 MHz and recover a transmission after a short delay
- Turn three log pages and collect evidence
- Enter SEA, LIGHT, SKY to restore the relay, with error feedback and retry
- Review a field notebook
- Choose either ending and reconsider it
- Toggle optional sound or reset progress with confirmation

## State and accessibility
One versioned state object tracks clues, visited scenes, log page, tuned frequency, and ending. localStorage persists progress. Malformed or blocked storage falls back safely to memory. Duplicate clue collection is prevented. An incomplete investigation cannot open the ending by changing the URL. Buttons, labelled inputs, focus styling, modal dialogs, live feedback, image alt text, responsive layouts, and reduced motion support are included. Sound starts only after user input. Every story clue is available as text.

## Demo route
Map > Listening room > tune 88.4 > Recover transmission > Archive > next page twice > Add log > Rooftop relay > SEA, LIGHT, SKY > map > Broadcast desk > choose an ending. Try roof before archive to demonstrate non-linear exploration and feedback.

## Media and attribution
The story and all characters are fictional. Station artwork: AI-generated with OpenAI ImageGen for this project, October 14, 2026. Prompt: abandoned 1980s coastal radio control room at night, analog mixing console, tape machines, amber lamp, papers, foggy sea and radio mast, forest green shadows, aged ivory highlights, no people, readable text, logos, or watermark. The included station.jpg is compressed from that generated artwork. It serves as consistent environmental artwork across scenes. The station-hum.wav ambient loop is an original synthesized 110/220 Hz tone created for the project. No external assets or libraries are used.

## Submission
Prepared as an individual submission.
