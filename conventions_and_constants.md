# Conventions and Constants

### Terminology

Word = An English word we use in the experiment, i.e., chalk, power, brown, etc.

Anagram = A particular shuffling of a word, i.e. HALCK, REWOP, etc.

Subject = Someone who takes the experiment. (I think it's better than participant.)

Phase = A unique trial/calibration/black screen by a certain subject.

Trial = A unique phase, which is also a trial (solving an anagram).

Part = Either 1st (calibration) part or easy, medium, or hard 2nd part of the planned experiments. 

Bigram = Two-letter combination

In-word-bigram = Bigram in the solution word

Letter Gaze Sequence (LGS) = Sequence of letters read by the subject in a trial



### Guiding principles of cleaned and prepared data

- All available readings are included (location of eyes in 3d space, pupil dilation, gaze, fixation, etc.) across all timestamps. Keep the calibrations, black screens, as well as anagrams. (For the six-number calibrations, there were two - in the middle and end of the experiment, thus their MediaNames are labeled: '123456_1' and '123456_2', to indicate the six-letter calibration at the middle and end of each experiment, respectively.)
- I have given polar coordinates (in pixels, degrees) to the nearest letter/number location center, along with an identification of that letter/number (1 through 5 or 1 through 6 going middle left clockwise). I've done this for both gaze and fixation.
- Cartesian coordinates now have a bottom-left origin (as opposed to a top-left).
- Saccade Index/Number, Fixation Index/Number, and Timestamp all start from the beginning of each phase (trial/calibration/black break image). (As opposed to starting from the beginning of each recording/subject.)
- The `PhaseName` uniquely identifies each phase and is made up of the subject ID number + the MediaName ('25_HALCK', '17_12345', '5_Black_Screen', etc.)
- Be as well documented, clear, and simple as possible so that future students can easily build on the code. 

