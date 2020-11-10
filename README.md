# Arduino Rompler


###
After downloading the project make sure to clone all submodules, too.
```
git submodule update --recursive --remote
```


## Compilation and Uploading
Compile and Upload Rompler:
```
platformio run -e rompler -t upload
```

Compile and Upload Sine Test:
```
platformui run -e sine_test -t upload
```

## TODOs

- [ ] Improve Readme.md
- [ ] Create a dedicated (external) library for the I2S Code. 
[Use Library Specification](https://arduino.github.io/arduino-cli/latest/library-specification/)
- [ ] Refactor Code 
- [ ] Implement new Feature: Change Start Pos, Sample Len, Playback Direction
- [ ] Buy an Arduino SD Card Reader and implement it in the code 