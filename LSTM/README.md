# IMDb reviews classification using LSTM (Keras)

This is an educational project of natural language classification.\
It utilizes the IMDb reviews dataset.\
Main reason of using LSTM layers instead of fully-connected layers is the ability of LSTM to process sequences of data. It means that LSTM is capable of learning from relative positions of words and their role in the text.

Key features of the project:
* Dataset lookup
* Preprocessing (duplicate removal, label encoding, string vectorization)
* Training of NN with LSTM layers
* Performing predictions on a test dataset (~0.85 accuracy)

## Showcase of predictions

(10702) ---------------\
Original review text: "I'm a huge fan of Ivan Reitman-I loved Evolution and who didn't like Ghostbusters? From the trailer you already know that Uma's character will get dumped by Luke's.So the build-up is obviously towards the moment when she unleashes her superpowers on him.But the pay-off is just not there.The shark tossing did manage to get a (slight) giggle but once again, it was all in the trailer. No one does breathless quite like Uma and Luke is diet Owen on his good days.If not for Riann Wilson you would sit there with a constipated smile until your cheeks start to cramp.This is a comedy,right?  It's not awful-it just sits there like a stale cracker behind the fridge.This could have been such a brilliant send-up of Superhero movies and Feminism but fails on both counts.Let's see if Jason Reitman can salvage the family name."\
Original sentiment: negative\
Predicted sentiment: negative\
✅ Right

(12626) ---------------\
Original review text: "I loved This Movie. When I saw it on Febuary 3rd I knew I had to buy It!!! It comes out to buy on July 24th!!! It has cool deaths scenes, Hot girls, great cast, good story , good acting. Great Slasher Film. the Movies is about some serial killer killing off four girls. SEE this movies"\
Original sentiment: positive\
Predicted sentiment: positive\
✅ Right

(120) ---------------\
Original review text: "this movie gets a 10 because there is a lot of gore in it.who cares about the plot or the acting.this is an Italian horror movie people so you know you can't expect much from the acting or the plot.everybody knows fulci took footage from other movies and added it to this one.since i never seen any of the movies that he took footage from it didn't matter to me.the Italian godfather of gore out done himself with this movie.this is one of the goriest Italian movies you will ever see.no gore hound should be without this movie in their horror movie collection.buy this movie no matter what it is a horehounds dream come true."\
Original sentiment: positive\
Predicted sentiment: negative\
❌ Wrong

(231) ---------------\
Original review text: "I think this is one hell of a movie...........We can see Steven fighting around with his martial art stuff again and like in all Segal movies there's a message in it, without the message it would be one of many action/fighting movies but the message is what makes segal movies great and special."\
Original sentiment: positive\
Predicted sentiment: negative\
❌ Wrong
