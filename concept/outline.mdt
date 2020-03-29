# Concept

_Gaudi_ is going to be an online platform where friends or even strangers primarily meet up to have fun together - hence the name. The players meet in _rooms_ to competitively guess words, taking turns. Each turn, one of the players has to explain a given word, while all others listen carefully and try to guess the word being described as fast as possible. Guesses are entered in chat window; correct guesses will be rewarded by points, wrong guesses are shown to all other users as well, so narrowing down on common ideas is possible. The player describing the current word is also rewarded with points, depending on how fast the other players are able to correctly guess the word in question. 

# Key Concepts

## Players

Players are simply identified by their respective user names which need not be unique across the application. Players cannot register, but their information stored persistently in their session, so that information is retained once entered. 

## Rooms

Rooms are identified by an arbitrary name (which may consist of letters & numbers) and can be joined by the players just by providing the room's name. 
Rooms are displayed on a single page, which contains a list of players to the left, some visual aid in the middle and the chat to the right. Apart from the players' names, the list also features the points obtained as well as an avatar, should the player choose one. The center part features the already guessed words as a word cloud, which changes dynamically:

- new words pop up automatically
- frequently guessed words become more pronounced (i.e. have a bigger font size)
- after a given interval, words fade away automatically
- words are always moving about slightly 
  (as in a Brownian motion; this makes it more interesting to look at)

The right hand side features a chat window where arbitrary messages _and_ guesses are inserted. Guesses of players are retained if wrong, but the window will replace correct guesses with a success message indicating which player made a correct guess. 
(Optional: if the guess is very similar to the target word, for instance as measured by the Levenstein distance, then a hint pointing out this fact is given)

## Rounds

When a room is created, a number of rounds (between 1 and 10) and a time limit for each round is specified. When it is the turn of the currently explaining person (all players take turns in round-robin fashion), he gets presented with several choices (i.e. sampled words) to choose one from. In this way, he or she is able to choose the words he or she can explain best or knows in the first place. 

## Words

The words to be guessed are called _targets_. Those targets are sampled from a list which is chosen or provided upon room creation. The targets are individual words, which may be verbs, nouns or adjectives.
A word has several _representations_, which are language-specific. Instances include "with Kanji", "Hirgana only", "Romanization only" for Japanese and "Simplified", "Traditional" and "Pinyin" for Chinese. The representation to be guessed is chosen at the same time the word list is selected. 
(Note: the person explaining always sees all representations, as some representations do not uniquely identify a word.)

## Word lists

The word lists contain words either belonging to a specific level of difficulty (i.e. A1 to C2 or HSK1 to HSK6) or belonging to a specific category (i.e. celebrities, vegetables, business etc). 
(Optional: those lists may also correspond to vocabulary lists from frequently used language learning materials)

# Communication

All rooms feature a WebRTC voice chat which the player automatically joins when he enters the room. This channel is also the one used for all players to listen to the explanations. Furthermore, the text chat may also be used for communication purposes. 





