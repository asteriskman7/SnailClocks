# SnailClocks 🐌

Starting on Friday, July 27, 2018 and for a total of 12 consecutive Fridays, I created various types of clocks that are snail themed in some way.

\# | Date | Description | Link
-------|------|-------------|-----
1      | July 27, 2018 | [Hilbert Snail Clock](#hilbert-snail-clock) | https://jsfiddle.net/asteriskman/bwpeL0qk/embedded/result/dark/
2      | August 3, 2018 | [Snail Shell Clock](#snail-shell-clock) | https://jsfiddle.net/asteriskman/9z4kmjts/embedded/result/dark/
3      | August 10, 2018 | [Snail Slime Clock](#snail-slime-clock) | http://jsfiddle.net/asteriskman/51jyx9Lt/embedded/result/dark/
4      | August 17, 2018 | [Snail Walk Clock](#snail-walk-clock) | https://jsfiddle.net/asteriskman/6n240esv/embedded/result/dark/
5      | August 24, 2018 | [Parallax Snail Clock](#parallax-snail-clock) | https://jsfiddle.net/asteriskman/6tgsfp2w/embedded/result/dark/ 
6      | August 31, 2018 | [Snail Destination clock](#snail-destination-clock) | https://jsfiddle.net/asteriskman/ytf79ugn/embedded/result/dark/
7      | September 7, 2018 | [Falling Shells Clock](#falling-shells-clock) | https://asteriskman7.github.io/SnailClock7/
8      | September 14, 2018 | [Hypnosnails Clock](#hypnosnails-clock) | https://asteriskman7.github.io/SnailClock8/
9      | September 21, 2018 | [Space Snail Party Clock](#space-snail-party-clock) | https://asteriskman7.github.io/SnailClock9/
10     | September 28, 2018 | [Psychedelic Abstract Clock](#psychedelic-abstract-clock) | https://asteriskman7.github.io/SnailClock10/
11     | October 5, 2018 | [SASA Control Room Clock](#sasa-control-room-clock) | https://asteriskman7.github.io/SnailClock11/
12     | October 12, 2018 | - | -

## Hilbert Snail Clock
The snail traces out the path of a level 6 [hilbert curve](https://en.wikipedia.org/wiki/Hilbert_curve) over the course of an hour. The highlighted pulse traverses the current path once per minute.

## Snail Shell Clock
The current time winds its way up from the center of the snail's shell following a [logarithmic spiral](https://en.wikipedia.org/wiki/Logarithmic_spiral). The center of the spiral is infinitely distant in the future.

## Snail Slime Clock
A single snail goes from one point on the edge of a circle to another point on the edge of a circle, leaving a [slimy trail](https://en.wikipedia.org/wiki/Snail_slime) behind it. It chooses its path such that, over time, it draws the current time.

## Snail Walk Clock
A single snail [walks](https://www.britannica.com/animal/gastropod/Locomotion) around the clock face leaving a multicolored trail in its wake. It fills in the clock so that what it leaves slime-free is the current time. If it gets stuck too long in its own trail it takes a big leap towards the center in the hope that it will find a clean area that needs filled.

## Parallax Snail Clock
A snail travels along the ground on a path where the current time enters the picture just as the minute changes. The background simulates depth by faking [parallax](https://en.wikipedia.org/wiki/Parallax). The hight of the hills and mountains and the color of the grass are controlled by a type of [Perlin noise](https://en.wikipedia.org/wiki/Perlin_noise).

## Snail Destination Clock
An [escargatoire of snails](https://researchmaniacs.com/CollectiveNouns/Animals/What-is-a-group-of-Snails-called.html) come together in the middle of a field to create the digits of the current time. Unfortunately, a hungry bird comes by and catches them off guard.

## Falling Shells Clock
Many snail shells (each, one of two colors) are dropped from above and fall down through a [Plinko](http://priceisright.wikia.com/wiki/Plinko) style board. When they come to rest, their final arangement shows the current time. [MAGIC!](https://en.wikipedia.org/wiki/Magic_(illusion)) (The secret is to run the simulation once while not displaying it to find the final position of the shells, decide their colors, and then run the identical sim again with the calculated colors.)

## Hypnosnails Clock
The eyes of two hypnosnails will take over your mind while displaying the time. Every digit is made from many connected points that create the digit outline. Over time, those points are [morphed](https://en.wikipedia.org/wiki/Morphing) from their position in the previous time's digit to their position in the next time's digit. The morphing has some [Perlin noise](https://en.wikipedia.org/wiki/Perlin_noise) applied to keep your mind open to suggestion.

## Space Snail Party Clock
Snails are out for a space party, orbiting their favorite point. As they move around, they take up positions so that you will see the current time when they line up properly once per minute. Snails in the back must be careful so that, when it's not yet their time to shine, they will be [eclipsed](https://en.wikipedia.org/wiki/Eclipse) by their friends in front.

## Psychedelic Abstract Clock
The snail has asked 3 of its friends, a duck, a sheep, and a robot, to help it tell the time. Each sits on the end of a clock hand (hour, minute, second, millisecond) but instead of revolving around the center of the clock, each hand revolves around the tip of the hand slower than itself. The 4 friends may have consumed some [mind altering substance](https://en.wikipedia.org/wiki/Lysergic_acid_diethylamide) before producing this clock. Groovy!

## SASA Control Room Clock
Following their heros of NASA's [Apollo 11 Mission](https://www.nasa.gov/mission_pages/apollo/missions/apollo11.html), the snails are on their way to the moon. The live transcript includes the current time and the orbit display shows the snail-craft's current position as it orbits the Earth once per hour. The transcripts are generated with a size 2 ngram [Markov chain](https://en.wikipedia.org/wiki/Markov_chain) extracted from the [Apollo 11 transcripts](https://www.jsc.nasa.gov/history/mission_trans/apollo11.htm).

## CLOCK 12
