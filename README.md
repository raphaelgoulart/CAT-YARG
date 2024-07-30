# CAT-YARG
The main idea of this repo is to modify CAT so it accepts CH/YARG exclusive features (Expert+ kick notes, open notes, tap regions etc.) rather than erroring out due to invalid notes. If you chart primarily for RB3, please use [the original](https://github.com/abefacciazzi/CAT) instead.

## TODO
- Create drums animations
  - [x] Silently ignore Expert+ kicks (note 95) instead of erroring out;
  - [x] For velocity 1 snare notes, auto-generate Snare Rim animation notes instead of Snare Hard (togglable);
- Automatic reductions (drums)
  - [x] Silently ignore Expert+ kicks (note 95) instead of erroring out;
- Automatic reductions (5-lane)
  - [x] Silently ignore tap markers;
  - [x] "Move opens to green" toggle for each difficult (default: off/on/on for H/M/E respectively);
  - [x] Add support for PART GUITAR COOP track;
- Reduce 2x bass pedal
  - [x] Move to note 95 instead of deleting;
- General
  - [x] Add "Guitar Coop" to all 5-lane related functions
  - [ ] Ensure all functions still work even if the charts have non-RB3 features in them;
- Pro Guitar/Bass
  - [ ] (maybe) Add support to PART REAL_GUITAR_COOP and REAL_RHYTHM, **if** those get added to YARG;
- CARV
  - This just hangs in my PC, so I won't be touching that. Sorry!
