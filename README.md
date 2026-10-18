# Aero Atlas

An interactive 3D explorer of Formula 1 regulations and aerodynamics, from the 1.5-litre formula of 1961 to the active-aero cars of 2026.

Built by Chetan Payyavula, with AI assistance (Claude) for the code. Live site: https://chetan-payyavula.github.io/aero-atlas/

## What it does

- **Regulation car for every season.** A generic F1 car built from that year's FIA figures: overall width, front and rear wing width, rear wing height, overhangs, wheelbase, tyres and minimum weight. Every figure links to its source. Where no source gives a rule, the page says so and shows the approximate size the model uses.
- **15 rule eras, each with its own shape.** Cigar-bodied 1960s cars, the 1968–69 high strut wings, 1970s wedges with box sidepods and tall airboxes, ground-effect wing cars with skirts, short dart-shaped turbo-era sidepods, coke-bottle sidepods from 1989, grooved tyres from 1998 to 2008, the halo from 2018, deep undercut sidepods and tunnel floors from 2022, and 2026 movable wings.
- **Legal box.** Shows the space the rules allow the bodywork and wings to use.
- **Airflow view.** Illustrative streaks coloured by local speed, not CFD.
- **Active aero and DRS.** Corner Mode and Straight Mode buttons for 2026; a DRS button for 2011–2025.
- **Compare.** Overlay any other era as a see-through ghost car, with a side-by-side table of the rules.
- **Season grids.** Every team from 1961 to 2026 with its chassis, engine, drivers and constructors' championship position. The 2026 season shows standings so far.
- **Radical designs.** 25 cars that read the rules differently, from the Lotus 25 monocoque and the Williams FW14B active car to the Brawn double diffuser and Mercedes' DAS steering. Each one explains what the rules allowed, what the team did and how it turned out, with a button that highlights the affected area of the car.
- **History tour.** A skippable intro on the first visit sweeps the car through every era; "Play history" reruns it.
- Works on desktop and phone, in light and dark mode.

## Run it

Open `index.html` in a browser. It needs an internet connection to load three.js and the fonts.

To publish it, put `index.html` in a GitHub repository and turn on GitHub Pages, or drag the folder into Vercel.

## Built with

- three.js 0.160.1, with all car geometry built in code: lofted chassis and sidepod sections, NACA-style aerofoils, and lathed tyres
- Plain HTML, CSS and JavaScript in a single file, with no build step

## Data and credits

- Season grids: [F1DB](https://github.com/f1db/f1db), licensed CC BY 4.0
- Regulation figures: FIA and Formula1.com articles, F1Technical, Wikipedia, Autosport, RacingNews365 and others. The full source list is at the bottom of the page.
- Where sources disagree, the page shows both values.

The 3D car is a generic regulation model, not a replica of any team's car. This project is not affiliated with Formula 1, the FIA or any team.
