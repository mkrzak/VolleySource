# VolleySource

Volleyball materials for the County League teams at Cambridge Volleyball Club, compiled by Monika Krzak (County Women Assistant Coach and Beach Volleyball Ambassador).

**Live site:** https://mkrzak.github.io/VolleySource/

One self-contained page (`index.html`) with ten sections:

- **Dynamic Warm-up**: 17 exercises in 7 phases, with clips, plus a dance warm-up video (`dance-warmup.mp4`)
- **S&C Program**: 4-day at-home program, workouts from [The Art of Coaching Volleyball](https://www.theartofcoachingvolleyball.com)
- **Gym Program**: agility, ballistics & plyo (10 drills) and isometrics (16 holds)
- **5:1 Receive**: base positions and serve-receive formations for all six rotations, with a rotation-fault checker
- **5:1 Defence**: perimeter (2-0-4) and rotational (2-1-3) defence; drag their hitter to see the block and defence move
- **CVA Scoresheet**: animated guide to filling in the CVA county league scoresheet
- **FIVB Scoresheet**: animated guide to filling in the FIVB international scoresheet, following the FIVB instructions
- **CVA Rules 25-26**: key rules from the CVA County League Rules
- **FIVB Rules 25-28**: faults, delays and misconduct, refereeing, and the referee hand signals
- **CVA Fixtures**: 2026-27 women's and men's tables, fixtures and results from the [CVA website](https://www.cambsvolleyball.org.uk/), with buttons for each CVC team's games and ref duties
- **NVL Fixtures**: 2026-27 tables, fixtures and results from [VolleyZone](https://competitions.volleyzone.co.uk/) for every NVL division with a CVC team (women D1 North, D2 Central, D3 Central; men D1 South, D3 Central)
- **About Me**

Animated drills now have their own site: [VolleyDrills](https://mkrzak.github.io/VolleyDrills/).

Everything (clips, images, scripts) is built into `index.html`, except the dance warm-up video, `dance-warmup.mp4`, which sits next to it. Keep the two files together and it also works offline: just open `index.html` in a browser.

## Update the site

Replace `index.html` with the new version, then:
```
git add .
git commit -m "Update VolleySource"
git push
```
GitHub Pages republishes automatically after every push (Settings → Pages: deploy from branch `main`, folder `/ (root)`).
