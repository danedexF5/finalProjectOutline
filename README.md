# finalProjectOutline

Requirements

Create a requirements document for your final project. The document's purpose is to help you think through what you really need to do and to break it down into small steps that can be accomplished more easily.

Your document can be in any structure or form that works for you, but should include the following information:

Description

**Write out a detailed description of your project, what you want it to do, and, in general, how it will do it.**

*General Description: I'd like to create a web app that maps users to dogs. It will be based on what a user inputs on a home page, via a series of questions to a database of dogs. The dogs will have a variety of features that will match to a user based on the input.*


**Write User Stories and associated requirements.**

**Research user stories and then write them for your project. For each user story write a description of how this will be accomplished in your project. For example, a user story might be:**

As someone searching for a dog, I want to find a dog that is a good match for my wants and lifestyle.

Description: 

+ A home page will be created for the user.
+ The page will have questions about the user and about dogs. The user questions will have several options to select from. The question answers will map to the dog that has traits that match.

User Questions:

+ "How many hours per week do you work outside of your home?" 20 or less, 30 or less, 40 or less, 50+
+ "How active are you?" Not active, Somewhat active, Very active
+ "Which size dog do you prefer?" Huge, Large, Medium, Small, Toy
+ "Living situation?" House, Condo, Apt
+ "Fenced in yard?" Yes, No
+ "Do you have children?" Yes, no
+ "How much does shedding bother you?" A lot, A little, Doesn't
+ "Energy level of your dog?" Very playful, somewhat playful, likes to lounge
+ "Friendliness?" Very friendly, somewhat friendly, aloof

Dog Traits:

+ Attention needs: A lot, more than avg, avg, little
+ Exercise needs: little, average, needs a lot
+ Size: huge, large, medium, small, toy
+ Space needs: big space, medium, not much
+ Outdoor access: Needs it, doesn't need it
+ Good with kids: Yes, no
+ Sheds: Heavy, medium, little to none
+ Energy: Very energetic, medium, low energy
+ Friendly: Very, medium, not

**Stretch**
*Someone that likes the match and wants to see adoptable dogs nearby.*

+ get api from petfinder https://www.petfinder.com/developers/api-docs
+ provide link with the dog that launches petfinder page with local results

*Users of the app want to give feedback on the categories*

+ provide simple field for users to give feedback. Yes/No type answers.

**Identify Unit Tests**

User stories are excellent tools for identifying what tests you need to write. Use them to identify behaviors to test for each user story.

+ Does user/size return correct dog/size
+ Does user/hoursWorked map to dog/Exercise
+ Does user/children map to dog/children

**Stretch Tests**

+ does the link display a page with the correct dogs/location
+ is user feedback displayed

**Draw pictures**

*Pictures in separate file*



**Identify your Minimum Viable Product**

**Time is very, very, limited for the final project. You need to identify the features that your project absolutely must have. This is called the minimum viable product (MVP). You should make sure the MVP is a size your feel confident you can complete in one week. One week.**

*MVP is everything outside of stretch*

Questions:
1) Um, how am I going to do this?
2) was thinking of populating dog database with a arbitrary number of dogs. Enough to return a variety of results. Good?
3) How to display the user inputs for the categories. Drop down, check off, etc?
4) How to connect the user to correct dog, algorithm?

[Imgur](http://i.imgur.com/7rzRtCU.jpg?1)
