# Project Nikaky: Classified 
## 4th Quarter CS Project 
Contributors: Kywee Maristela, Nissi Palada, & Kaleena So 

## Project Decription
Classified: Project Nikaky is a text-based choose your own adventure game set in 3035 where the unfortunate effects of Global Warming have made the Earth inhabitable and humans have occupied space. However, hope arrives when you discover a deactivated time machine created by 3 scientists, Dr. Juliene Palada PhD., Dr. Chrismyshell Maristela PhD., and Dr. Kaleena So PhD. in 2022 within the grounds of the Philippine Science High School - Main Campus. 

This machine will allow you to travel to the past, warning the world before these unfortunate events take place. Thus, the government sends you and other engineers on a mission to get the machine working. Hidden within the school corridors is the reactivation key to the time machine you must uncover before your time runs out due to the limited supply of oxygen. 

The reactivation key requires a set of codes hidden within the school which can be obtained by answering some questions. These questions will be about certain STEM topics taught in the school and school trivia. 

A dark, abandoned place will be a challenge for you and your team; thus, the right decisions and answers are crucial. Good luck in saving the future, Engr. 

## Reason behind the Project
We mainly wanted something sci-fi or post-apocalyptic themed set on the grounds of PSHS-MC, incorporating our passion and common interest in STEM with a sci-fi setting. We brainstormed for a plot until we arrived at time-traveling, and eventually came to the idea of sending messages calling to help the Earth would be the main objective of the characters. This is applicable in today’s society as warnings from scientists help shape our future. As future women in STEM, we felt that trust in science and data is a relevant topic that would fit well for our project, as well as implement a fun and engaging game centered around time travel. 

## Plot Summary 
## Planned Pages 
### / 
This is the home page. Here, the user has the option to continue their previous game or start a new one. The user will also have access to the **Learn More** page and the game gallery

### /intro 
This is the game's starting page. Here, the user will enter their engineer profile, including one's name and Engineering major (choices: Software, Mechanical, Chemical). They will also be informed about the game mechanics as well as a short description of what's to come. 

### /game 
This is the main page where the game occurs. It is where the user will answer questions, make choices, and find the reactivation key around the school. JavaScript will be used to dynamically update the webpage based on the user answers. 

### /results 
This is the end of the game where the user will be shown their fate, whether they success or fail the mission from the choices they've made. From their choices, this page will showcases all possible paths one could've made for the different outcomes. This will contain a button that gives users the option to see how much their choices differed from others that have played the game. Said button redirects the user to /statistics. 

### /statistics 
Here, the user will see a summary of answers and how much of those who played matched his choices. On the case of quiz quiestions, the users are given access to check the percentage of players who got said questions right or wrong. 

### /learn-more
As this topic tackles the importance of trusting the science as well as watching out for global warming, the group has decided to add a page that provides the user with resources they can check out to learn more about an ever growing problem. 

### /game-gallery 
Set in the PSHS-MC Campus, this page will contain photos of the campus users can explore. However, these photos are for viewing purposes and do not contain clues in the game. 

## Sample Questions 

### _Choice_
1. You walk up to the second floor and see a man looking out the window, do you: 
```HTML
<select>
  <option>a) Walk up and talk to the man  </option>
  <option>b) Keep on track and look for the next room </option>
</select>

``` 

### _Trivia_
2. [Multiple Choice], Subejct: Chemistry, **C6H12O8 is the chemical formula of what compound?**

```HTML 
<select>
  <option> a) table salt</option>
  <option> b) glucose </option>
  <option> c) fructose </option>
  <option> d) sucrose </option>
</select> 
```
3. [True or False], Subject: Math, **Identify if this following statement is True or False: O is an example of a Whole Number**

``` HTML 
<select> 
  <option> True </option> 
  <option> False </option> 
</select> 
``` 
4. [Identification], Subject: Statistics, **What is refered as the study and manipulation of data? **
```HTML 
    <input type="text" placeholder="Answer">
```
