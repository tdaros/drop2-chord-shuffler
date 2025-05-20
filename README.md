# Drop 2 Chord Shuffler Web App

## Overview

The Drop 2 Chord Shuffler is a simple, single-file HTML web application designed for musicians, particularly guitarists, to practice and internalize Drop 2 chord voicings. It allows users to select various musical parameters (root notes, accidentals, chord qualities, inversions, and string sets) and then generates random combinations of these parameters to display a chord to practice.


## Features

* **Random Chord Generation:** Displays a random Drop 2 chord based on selected criteria.
* **Customizable Parameters:**
    * **Root Notes:** C, D, E, F, G, A, B
    * **Accidentals:** # (sharp), b (flat) - can be combined with root notes.
    * **Chord Qualities:** M7 (Major 7th), m7 (minor 7th), 7 (Dominant 7th), m7b5 (minor 7th flat 5 / half-diminished), dim7 (diminished 7th).
    * **Inversions:** Root Inversion (1), 1st Inversion (3), 2nd Inversion (5), 3rd Inversion (7).
    * **String Sets:** Lower Set, Middle Set, Higher Set (conceptual sets for guitar string groups).
* **Interactive Configuration:**
    * Checkboxes allow users to easily enable or disable specific options for each parameter.
    * Clicking the title of a configuration category (e.g., "Root Notes") toggles all checkboxes within that category.
* **Permutation Counter:** Keeps track of how many chord permutations have been generated during the session.
* **Keyboard Shortcuts:**
    * Press `Enter` or `Space` to generate a new chord permutation.
* **Single File Application:** All HTML, CSS, and JavaScript are contained within a single `.html` file for portability and ease of use.
* **Responsive Design:** The layout adapts reasonably to different screen sizes, though it's primarily designed for desktop use.

## How to Use

1.  **Download:** Save the `drop2_shuffler.html` (or the provided HTML code) file to your local computer.
2.  **Open:** Open the `drop2_shuffler.html` file in any modern web browser (e.g., Chrome, Firefox, Safari, Edge).
3.  **Configure (Optional):**
    * Scroll to the "Configuration" section at the bottom of the page.
    * By default, most options are enabled.
    * Check or uncheck the boxes to include or exclude specific roots, accidentals, qualities, inversions, or string sets from the random generation.
    * To quickly select/deselect all options in a category, click on the category title (e.g., click "Chord Qualities" to toggle all quality checkboxes).
4.  **Generate Chord:**
    * Click the "Generate Permutation" button.
    * Alternatively, press the `Enter` key or the `Space` key.
5.  **Practice:** The randomly selected chord, its inversion, and the string set will be displayed in the center of the page. Use this prompt for your practice routine.
6.  **Repeat:** Generate as many new chords as you like. The counter at the top-left will show how many permutations you've generated.

## File Structure

The entire application is contained in a single HTML file. This file includes:

* **HTML:** The structure of the page (display area, buttons, configuration sections).
* **CSS:** Styles for the visual presentation (layout, colors, fonts).
* **JavaScript:** The logic for:
    * Populating configuration options.
    * Handling user input (button clicks, key presses, configuration changes).
    * Generating permutations of selected chord parameters.
    * Randomly selecting and displaying a chord.
    * Updating the permutation counter.
    * Toggling checkboxes via category titles.

## Technical Details

* The core logic for generating permutations involves creating a list of all possible combinations from the user-selected options for roots (with accidentals), qualities, inversions, and sets. A random choice is then made from this list.
* The application uses vanilla JavaScript, HTML, and CSS, requiring no external libraries or frameworks.

## Potential Future Enhancements

* Visual display of the chord on a fretboard diagram.
* Audio playback of the generated chord.
* More advanced configuration options (e.g., specific string sets for different Drop 2 voicings).
* Saving/loading user configurations.

---

Enjoy your practice!
