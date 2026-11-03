# Cruise control on a ring road: interactive simulators

Two browser simulators accompanying the paper *Cruise control on a ring road in a cumulative-flow traffic model: limit flow, transient regime, calibration and microscopic test*.

- `macroscopic.html`: the cumulative-flow models KW, DKW, CC and DCC on a ring of sections.
- `highwayenv.html`: a JavaScript reimplementation of HighwayEnv's IDM/MOBIL vehicles on a multi-lane ring and on the 260 m ring of Stern et al. (2018), with a speed cap, FollowerStopper, PI with saturation and ACC controllers.
- `index.html`: landing page linking both.

Everything runs client-side; no build step and no server code.

## Publishing with GitHub Pages

Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
The site is then available at `https://<user>.github.io/<repository>/`.
