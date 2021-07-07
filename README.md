![Python](http://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=ffffff)
![Linux](http://img.shields.io/badge/-Linux-0078D6?style=for-the-badge&logo=linux&logoColor=ffffff)
# Human Computer Interaction (HCI)
# Controlling Mouse Motions Using Eye Blinks, Head Movements and Voice Recognition
This is a mini project at NITK Surathkal.
## Dataset-

Can be found here - 
https://github.com/Akbhobhiya/Mouse_Cursor_Control_Handsfree/tree/main/Mouse_Cursor_Control_Handsfree-master/model

## Idea-
This system focused on the analysis of the development of controlling mouse cursor movements using human face, eyes and voice, application in all aspects. Initially, the problem do- main was identified and existing commercial products that fall in a similar area were compared and contrasted by evaluating their features and deficiencies. The usability of the system is very high, especially for its use with desktop applications. It exhibits UI which are sufficient for many real time applications and which allow handicapped users to enjoy many computing activities.

## HCI GUIDELINES Used

#### Consistency: 
Consistent design is intuitive design. It is highly useful and makes the world a better place. UI made in the project is consistent i.e same color and size of the icons use are eye loving and is of the same size. This will ease user for different background to interact
with system much easily. 
#### Get the Mapping Right: 
Mapping is the relationship between controls and the effect they have on the world. For example, the arrow buttons on a claw machine correspond to the movements of the toy grabbing mechanical arm. Norman explains, “when mapping uses spatial correspondence between the layout of the controls and the devices being controlled, it is easy to determine how to use them”. So, we have used natural controls only in our project, for example, if we move our head to left then cursor moves in left direction similarly, for right,up and down movement also.
#### Simplify Task Structure: 
Task level is to analyze the user’s needs and to structure the task domain in such a way, that a computer system can play its part. We have implemented the interface in such a way that the user can interact with UI simply in the small tasks. For example, in face control first task is to read input and after that
control the movements of mouse cursor.
#### Feedback:
When we interact with an everyday thing or product, we need something to communicate the result of our action: feedback. Without any immediate response, we are left wondering if our performed action has had any impact. So, we have implemented the feedback in our project very efficiently. For example, during controlling using face if face is moved left to move the cursor left side then it is visible on the frame as ”left” and similarly ”scroll mode on” is also shown when it gets on. And in case of controlling using voice we are showing the spoken sentences or the task that is executed on the terminal.
#### Cater to Universal Usability: 
Universal Usability is the design of things such that they are useful to as many people as possible. In designing application interfaces, we need to consider the type of user variation. Both in terms of cultural and linguistic background, also variations in the level of user understanding of the application. We have designed interfaces that cater to all levels &
#### classification of users:
novice to experts. For example, feedback is shown on the screen and in the voice control we have used easy and usable command actions like”move up 20”. We have implemented in such a way that any type of user can use the idea very easily.
#### Reduce Short Term Memory Load:
Recognition rather than recall. As Nielsen says, recognizing something is easier than remembering it. Minimize the user’s memory load by making objects, actions, and options available. The user should not have to remember information from one part of the dialogue to another. The commands used in project does not require any type of the remembering and is self explanatory and UI made it easy through lines in which direction user is moving the mouse pointer.

## How to setup the project
This project is built using Python3+, Django and ML . All the required libraries are listed in the first part of every code file.
Make sure to install all of them to run the project smoothly.

This is Django Project so run manage.py file with Django Uitility.

##### Clone the project
```sh
$ git clone https://github.com/Akbhobhiya/Mouse_Cursor_Control_Handsfree.git
$ cd Mouse_Cursor_Control_Handsfree
```
