# **Classified: _Mission 2022_ **
## 4th Quarter CS Project 
Contributors: K14 - Kywee Maristela, K17 - Nissi Palada, & K24 - Kaleena So 

## Project Decription
Mission 2022 is a text-based choose your own adventure game set in 3035 where the unfortunate effects of Global Warming have made the Earth inhabitable and humans have occupied space. However, hope arrives when you discover a deactivated time machine created by 3 scientists, Juliene Palada, Ph.D., Chrismyshell Maristela, PhD., and Kaleena So, Ph.D. in 2022 within the grounds of the Philippine Science High School - Main Campus. 

With the machine, your goal is to travel back to 2022 warning the world before these unfortunate events take place. The government sends you and other engineers on a mission to get the machine working. Hidden within the school corridors is the reactivation key to the time machine you must uncover before your time runs out due to the limited supply of oxygen. 

The reactivation key requires a set of codes hidden within the school which can be obtained by answering some questions. These questions will be about certain STEM topics taught in the school and PSHS-MC trivia. 

A dark, abandoned place will be a challenge for you and your team; thus, the right decisions and answers are crucial. Good luck in saving the future, Engr. 

## Reason behind the Project
We mainly wanted something sci-fi or post-apocalyptic themed set on the grounds of PSHS-MC, incorporating our passion and common interest in STEM with a sci-fi setting. We brainstormed for a plot until we arrived at time-traveling, and eventually came to the idea of sending messages calling to help the Earth would be the main objective of the characters. This is applicable in today’s society as warnings from scientists help shape our future. As future women in STEM, we felt that trust in science and data is a relevant topic that would fit well for our project, as well as implement a fun and engaging game centered around time travel. 

## Plot Summary 

## Data Processing 
After finishing the game and completing the form, users will get to see the summary of their journey–the choices they've made and answers to the questions they dind't guess correctly. Player answers will be consolidated and summarized to display the outcome majority of players, and which questions many found difficult. 

## Planned Pages 
### / 
This is the home page. Here, the user has the option to continue their previous game or start a new one. The user will also have access to the **Learn More** page and the game gallery

### /intro 
This is the game's starting page. Here, the user will enter their engineer profile, including one's name, Engineering major (choices: Software, Mechanical, Chemical), and other information. They will also be informed about the game mechanics as well as a short description of what's to come. 

### /game 
This is the main page where the game occurs. It is where the user will answer questions, make choices, and find the reactivation key around the school. JavaScript will be used to dynamically update the webpage based on the user answers. 

### /results 
This is the end of the game where the user will be shown their filled out profile and the results of the mission–whether they success or fail the mission from the choices they've made. From their choices, this page will showcase all possible paths one could've made for the different outcomes and outlines the one chosen by the user.

Additionally, this will contain a button that gives users the option to see how much their choices differed from others that have played the game. Said button will reveal a summary of the user's answers and how much of those who played matched their choices. On the case of quiz quiestions, the users are given access to check the percentage of players who got certain questions right or wrong. 

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
    <input type="text" placeholder="Statistics">
```
