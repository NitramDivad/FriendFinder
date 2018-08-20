# ** Node and Express with Heroku Assignment:  FriendFinder
#

FriendFinder App Details


In this activity, I was tasked to build a compatibility-based "FriendFinder" application -- basically a dating app but I added a twist:  the initial users are Looney Tunes characters. This full-stack site will take in results from users' surveys, then compare those answers with those from other users. The app will then display the name and picture of the user with the best overall match. 

Express will be used to handle routing, and the app will be deployed to Heroku so other users can fill it out.

The app contains 10 questions to be answered on a scale of 1-5 (1 being Strongly Disagree and 5 being Strongly Agree):

    * Your mind is always buzzing with unexplored ideas and plans.
    * Generally speaking, you rely more on your experience than your imagination.
    * You find it easy to stay relaxed and focused even when there is some pressure.
    * You rarely do something just out of sheer curiosity.
    * People can rarely upset you.
    * It is often difficult for you to relate to other people’s feelings.
    * In a discussion, truth should be more important than people’s sensitivities.
    * You rarely get carried away by fantasies and ideas.
    * You think that everyone’s views should be respected regardless of whether they are supported by facts or not.
    * You feel more energetic after spending time with a group of people.

Additionally, the user will be prompted to enter his/her name, and to provide an HTTP link to their photo.  All fields are required entry.

Compatibility is determined by a scoring methodology whereby the numerical answer to each question is subtracted from the same question for each Friend in the pool.  The differences (all absolute values) are added together to obtain a final score.  The lowest score will represent the most compatible friend.

A modal popup will be used to display the results of the Friend Finder.  It is possible to return more than one compatible friend.


## **Created by:** #

[David Martin](mailto:webdevelopment.du@gmail.com)

## **Links:** #

| [Friend Finder Site](https://still-earth-56143.herokuapp.com) | 
[Portfolio Site](https://nitramdivad.github.io/) | 
[GitHub](https://github.com/nitramdivad) |