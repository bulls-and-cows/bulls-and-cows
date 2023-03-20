# Bulls & Cows

Free online implementation of [Bulls and Cows game](https://bulls-and-cows.github.io). I have created it to play by myself and I'll be happy if someone else found it as a good option to spend time with a pleasure.

## Game rules

Your goal is to guess a secret number. It has 4 unique non-zero digits.

For each attempt I'll tell you how close your are with a number of bulls and cows.

Bull means your number and secret number have the same digit at the same place.

Cow means your number and secret number have the same digit but on the different places.

## Interface

The secret number is shown as `****`. Close to each attempts you'll see the number of bulls (b) and cows (c).

Use textbox to enter your number and press `Enter` key or `check` button.

`new` button lets you start new game at any time.

`show` button will stop game and display the secret number.

`hint` button puts suitable number in textbox.

## Example

IF:
- `5432` is a secret number
- `1234` is your number

THEN:
- `3` is a bull
- `2` and `4` are cows
- so, I'll tell you `bcc` - one bull and two cows

## Feedback

Feel free to [share any feedback](https://forms.gle/i2PLdVseFsTvLEaRA) with me.
