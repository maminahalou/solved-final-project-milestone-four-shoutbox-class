Download Link: https://assignmentchef.com/product/solved-final-project-milestone-four-shoutbox-class
<br>
<p class="ui header product-top-header" title="IT 511 Final Project Milestone Four: ShoutBox Class">Your final project for this course is the creation of a Virtual World Java application that results in a virtual world, complete with an object that will act as a human clone. (See Final Project Document for more information.) A virtual world with a human clone would not be complete without additional objects for interaction, so in this milestone, due in Module Eight, you will be responsible for creating a “ShoutBox” and another object that will keep your human clone from getting lonely, and a virtual world application that will test your objects.

Specifications for ShoutBox:

The ShoutBox object will allow you to shout messages into your virtual world. Your ShoutBox will have two ways of generating messages:

You can select from a list of canned messages to shout, orYou can have the ShoutBox generate a random message for you.

You must use data structures Array, ArrayList, or a HashMap to store the message data.

Canned messages: One data structure will store the canned messages. You can load this data structure with canned messages of your choosing. The shoutOutCannedMessage() method will loop through the data structure to first display all canned messages and allow the user to select one. The shoutOutCannedMessage() will return the selected message String. This String will be displayed in the virtual world. For now, your virtual world will be the output window.

Random messages: To generate random messages, you need to have a data structure that holds a list of subjects, another data structure that holds a list of objects, another that holds a list of verbs, another that holds a list of adverbs, and another that holds a list of adjectives. The lists you create can hold as many words as you would like. The shoutOutRandomMessage() method will use a random number generator that selects one word from each data structure to form a random message. Random messages will be in the following form: Subject – Verb – Adjective – Object – Adverb.

The generated message String will be returned. The String will be displayed by the ShoutBox in the virtual world. For now, your virtual world will be the output window.

Partial class diagram for the ShoutBox object:

ShoutBox

String shoutOutRandomMessage()

String shoutOutCannedMessage()

Examples of canned messages stored in the canned messages data structure (you can store as many canned messages as you would like):

“Hello World”“I am studying”“I am at work”

Example of subjects stored in the subjects data structure:

“I”“You”

Example of objects stored in the objects data structure:

“course”“homework”

Example of verbs stored in the verbs data structure:

“studying”“eating”“sneezing”

Example of adjectives stored in the adjectives data structure:

“funny”“prickly”“hard”“awesome”

Example of adverbs stored in the adverbs data structure:

“quickly”“everywhere”

The following critical elements will be addressed in this submission:

1.       The method shoutOutCannedMessage() loops through the data structure that stores the canned messages first to display all canned messages and allows the user to select one canned message.

2.       The method shoutOutCannedMessage() will return the selected message string.

3.       Your shoutOutRandomMessage() method should use a random number generator that selects one word from each data structure to form a random message. The random number generated should not exceed the bounds of your data. In other words, if you only have 5 words in a data structure, the random number generated should not be an index that has no word stored.

4.       The method shoutOutRandomMessage() should return a randomly generated message string in accordance with specifications, in the following form:

5.       Subject – Verb – Adjective – Object – Adverb (for example, “You read hard books quickly”).