# Mission Planner — Rocket Trajectory Calculator

**Plan a trip between planets and see the fuel and time it needs.**
Open `index.html` in a browser.

## What it does
Choose a rocket preset (or enter dry mass, fuel mass and engine efficiency, or **Isp**), a destination and a launch year. Click **CALCULATE TRAJECTORY** to see the results and an animated path.

## How it works
- **Hohmann transfer:** the most fuel-efficient two-burn way to move between circular orbits. It gives a departure burn, an arrival burn and a travel time in days.
- **Rocket equation:** links fuel, mass and engine efficiency to how much speed change (delta-v) the rocket can make.
- Uses real constants, such as the gravitational constant.

## Limits (honest)
- Assumes circular, flat orbits and ignores planet gravity during the trip, launch windows and atmosphere.
- It is a learning tool, **not** for real mission planning.

## What I learned
Why rockets are mostly fuel, and why timing matters when you travel between planets.

## Next steps
Add launch-window timing based on where the planets actually are.

---
Part of [Aadit's projects](https://github.com/TechTonicCortex/techtoniccortex).
