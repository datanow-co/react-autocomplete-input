### 24th January 2024 - 1.0.30
- trigger case sensitivity improvements. Props to karpov-sv
- autocomplete list scrollability improvement. Props to karpov-sv
- TS definitions fixes. Props to mcornejo

### 10th November 2023 - 1.0.29
- fix: onBlur handler called before handling onClick on item (https://github.com/yury-dymov/react-autocomplete-input/pull/122). Props to fabioimpe

### 27th October 2023 - 1.0.28
- close suggestion list on input blur fix (https://github.com/yury-dymov/react-autocomplete-input/pull/113). Props to fabioimpe

### 19th October 2023 - 1.0.27
- fix: bad positioning when inside a scrolled container (https://github.com/yury-dymov/react-autocomplete-input/pull/112). Props to fabioimpe 

### 12th October 2023 - 1.0.26
- onBlur prop type definition fix (https://github.com/yury-dymov/react-autocomplete-input/pull/111). Props to fabioimpe

### 5th October 2023 - 1.0.25
- Fixed wrong suggestion list position when text field is scrolled (https://github.com/yury-dymov/react-autocomplete-input/pull/108). Props to fabioimpe

### 29th September 2023 - 1.0.24
- Better spacer handling for caret position (https://github.com/yury-dymov/react-autocomplete-input/pull/104/). Props to jaredzwick

### 29th September 2023 - 1.0.23
- Fixed typescript issue (https://github.com/yury-dymov/react-autocomplete-input/pull/107). Props to szaleq 

### 10th September 2023 - 1.0.22
- Added typescript support (https://github.com/yury-dymov/react-autocomplete-input/pull/103). Props to jaredzwick

### 29th August 2023 - 1.0.21
- Added passThroughTab prop (https://github.com/yury-dymov/react-autocomplete-input/pull/102/). Props to jaredzwick

### 18th January 2023 - 1.0.20
- Fixing maxOptions handling for keyUp/keyDown events (https://github.com/yury-dymov/react-autocomplete-input/pull/92). Props to Alice Choi 

### 2nd October 2022 - 1.0.19
- Fixing edge case for one option, one character (https://github.com/yury-dymov/react-autocomplete-input/pull/78). Props to Nikhil Varma

### 23d April 2021 - 1.0.18
- New changeOnSelect Prop (https://github.com/yury-dymov/react-autocomplete-input/pull/55). Props go to Lazaro Hurtado :)

### 21st March 2021 - 1.0.17
- Fixing missing core-js in dependency list issue

### 9th March 2021 - 1.0.16
- Props to LazaroHurtado, now library supports several sets of triggers and options simultaneously (https://github.com/yury-dymov/react-autocomplete-input/pull/54)

### 2nd December 2020 - 1.0.15
- Introduced new `onSelect` callback — (https://github.com/yury-dymov/react-autocomplete-input/pull/53)
- Added `passThroughEnter` prop - to override behavior on `Enter` key press
- Updated deps and dev deps

### 8th July 2020 - 1.0.14
- Use PropTypes.elementType to support wrapped components - (https://github.com/yury-dymov/react-autocomplete-input/pull/44)

### 9th April 2020 - 1.0.13
- Deps update
- Replaced componentWillRecieveProps and findDOMNode with modern APIs https://github.com/yury-dymov/react-autocomplete-input/pull/41
- Added autocomplete on tab - https://github.com/yury-dymov/react-autocomplete-input/pull/42

### 17th June 2019 - 1.0.11
- Updated vulnerable deps

### 26th February 2019 - 1.0.10
- Custom spacer support (https://github.com/yury-dymov/react-autocomplete-input/issues/28)

### 17th January 2019 - 1.0.9
- Deps update

### 25th February 2018 - 1.0.8
- Correctly matching uppercase strings
- `minChats` options added to control the minimum amount of inputed characters before showing autocomplete option list

### 21st February 2018 - 1.0.7
- Component now can be also a function

### 3d February 2018 - 1.0.6
- Some corner cases fixed for autcomplete selections

### 24th September 2017 - Version 1.0.5
- Fixed empty prefix and regex issues https://github.com/yury-dymov/react-autocomplete-input/pull/10
- New props: offsetX, offsetY to control popup offset, and matchAny to catch options in the middle of words as well

### 21st August 2017 - Version 1.0.4
- Fixed "Click" bug: sometimes autocompletion failed to work after clicking on the option https://github.com/yury-dymov/react-autocomplete-input/issues/7

### 19th May 2017 - Version 1.0.3
- Adding `prop-types` package to support React 16+
