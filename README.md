Composition for Algorithmic Music Online

From the homepage, you can access three other pages: the Randomizer Page, the Remixer Page, and the Interpolator Page.

The Randomizer Page allows you to choose a "randomness" value by dragging your mouse either clockwise to increase it or counter-clockwise to decrease it, which is visually represented by a swirl that appears. You can select 1-7 songs, and then based on the randomness value, the songs' notes will be split up into chunks (the chunks' size is inverse of the randomness value) and then the chunks will be played in a random order.

The Remixer Page allows you to choose a tuning system with a slider, and then it will display a clock with the number of steps in the system surrounding it, and with lines drawn in between the numbers to display the fifths of that system. The number of semitones in the fifth for the system is written in the center of the circle. It's a pretty neat property that the fifth value for each system is relatively prime to the number of steps in the system, meaning every step gets exactly one line drawn to it. You can choose one song to play with the tuning system you've set. The default system is 12 tone even temperament.

The Interpolator Page allows you to choose 2 songs and how many cycles you want it to take to get from the first song to the second song. The first song chosen will be highlighted in green and its impact on the current notes being played is displayed by the opacity of the green music note. The second song chosen will be highlighted in red and its impact on the current notes being played is displayed by the opacity of the red music note. The notes being played are the weighted average of the notes of the two songs, with the weights beginning at 1 for the first song and 0 for the second song, then moving to 0 for the first song and 1 for the second song, with the weights changing by 1 divided by one less than the number of cycles it'll take to completely move between the two songs, which is 13 minus the chosen speed.

There are 7 songs to choose from, with their names and notes listed in songs.txt.
In order they are:
    "I Bet on Losing Dogs" by Mitski
    "Stop Breathing" by Playboi Carti
    "Masquerade Suite: Waltz" by Aram Khachaturian
    "Merry-Go-Round of Life - from 'Howl's Moving Castle' by Joe Hisaishi
    "sdp interlude" by Travis Scott
    "Axel F" by Crazy Frog
    "I'm God" by Clams Casino and Imogen Heap

The notes were derived from piano tutorials on youtube.
I won't bother linking them because I only used about half of their notes anyway and they were almost always the top result when searching the name of the song and "easy piano". I also don't remember which I actually used.

There are also 3 producer tags, one for each return button, that play when the return to the homepage buttons are pressed.
The producers they belong to are:
    Randomizer page: MexikoDro
    Remixer page: F1lthy
    Interpolator page: BNYX

The svgs are identical, just edited to be different colors and are from the public domain.

