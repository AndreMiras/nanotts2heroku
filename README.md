# NanoTTS to Heroku

Since NanoTTS is not available on Heroku, we build our own patched one.

## Build
Build a copy on your own Heroku instance using the `build-nanotts.sh` in a one-off Dyno:
```
heroku run ./build-nanotts.sh
```
The binary will be made available on [transfer.sh](https://transfer.sh).
You can upload it anywhere and make it available via [peterkeen/heroku-buildpack-vendorbinaries](https://github.com/peterkeen/heroku-buildpack-vendorbinaries).
