# Assignment 3: Part 1 Website Behavior

## Student Information
- Name: Nemanja Blagojevic
- MRU Username: nlag157

## Approach
By visiting https://mru-got-name.fly.dev/, I enter my MRU username (nblag157) where indicated.
Keeping my username constant, I modify the switches A and B and the numeric slider, pressing the 'Generate!' button for each combination. 
Combinations for switches A and B can be, but not limited to, 1. switches A and B are off 2. switch A is on and switch B is off 3. switch A is off and switch B is on 4. switch A is on and switch B is on. Combinations for numeric slider can be any value between 1 and 100. Using all 4 combinations of switches, I will make sure to test numeric slider exhaustively and systematically by assigning as many different values as possible to numeric slider until I see some pattern and behavior of numeric slider


For every option or combination, it displays link (https://www.asciiart.eu) on bottom half of the display. 


## Website Behavior

# If numeric slider is 0 

1st option - If switches A and B are off, it displays "Lady Ygritte Rivers, The Cruel" with picture of two sword

2nd option - If switch A is on and switch B is off, it displays "Queen Arya, The Cruel" with picture of two sword

3rd option - If switch A is off and switch B is on, it displays "Ser Jaclyn Sand, The Cruel" with picture of two sword

4th option - If switch A is on and switch B is on, it displays "Queen Arya, The Cruel" with picture of two sword


# If the numeric slider is set to a value between 1 and 18, inclusive

If numeric slider is between 1 and 18, the second part of the name becomes "The Cursed" with picture of wolf (Art by Shanaka Dias)

1st option - If A and B are off, it displays "Lady Ygritte Rivers, The Cursed" with picture of wolf

2nd option - If A is on and B is off, it displays "Queen Arya, The Cursed" with picture of wolf

3rd option - If A is off and B is on, it displays "Ser Jaclyn Sand, The Cursed" with picture of wolf

4th option - If A is on and B is on, it displays "Queen Arya, The Cursed" with picture of wolf


# If the numeric slider is set to a value between 19 and 39, inclusive

If numeric slider is between 19 and 39, the second part of the name becomes "The Bloody" with picture of sheep

1st option - If switches A and B are off, it displays "Lady Ygritte Rivers, The Bloody" with picture of sheep

2nd option - If switch A is on and switch B is off, it displays "Queen Arya, The Bloody" with picture of sheep

3rd option - If switch A is off and switch B is on, it displays "Ser Jaclyn Sand, The Bloody" with picture of sheep

4th option - If switch A is on and switch B is on, it displays "Queen Arya, The Bloody" with picture of sheep


# If the numeric slider is set to a value between 40 and 99, inclusive

If numeric slider is between 40 and 99, the second part of the name becomes "The Absurd" with picture of lion

1st option - If switches A and B are off, it displays "Lady Ygritte Rivers, The Absurd" with picture of lion

2nd option - If switch A is on and switch B is off, it displays "Queen Arya, The Absurd" with picture of lion

3rd option - If switch A is off and switch B is on, it displays "Ser Jaclyn Sand, The Absurd" with picture of lion

4th option - If switch A is on and switch B is on, it displays "Queen Arya, The Absurd" with picture of lion


# If numeric slider is 100

If numeric slider is 100, the second part of the name becomes "The Blessed" with picture of dog (I'm not 100% sure that's dog)

1st option - If switches A and B are off, it displays "Lady Ygritte Rivers, The Blessed" with picture of dog

2nd option - If switch A is on and switch B is off, it displays "Queen Arya, The Blessed" with picture of dog

3rd option - If switch A is off and switch B is on, it displays "Ser Jaclyn Sand, The Blessed" with picture of dog

4th option - If switch A is on and switch B is on, it displays "Queen Arya, The Blessed" with picture of dog


## Summuary

### Switches A and B
Whenever the switch A or B is modified, it changes the first part of the name. If switch A is on and switch B is off or if switch A is on and switch B is on, it displays the same name or title for both combinations. 


### Numeric Slider
Whenever numeric slider is modified, it changes the second part of the name. 

Since whenever switch A is on and switch B is off or if switch A is on and switch B is on, it displays the same result, we can assume that there are in total 15 different options to be displayed to screen, 3 possible combinations for the names for switches A and B, and 5 possible combinations for numeric slider

