# UASChecklist
# Game SDK Toolset 

Developing a game for training kids or adults to fly a drone is a challenge, this is not the toolkit.  UAST
is a group focused on safety and helping all of us learn about aviation safety culture.  Use this set of configuration
files to create multi level games with safety content designed for teaching and field uses.  


# C.E.O.P. CHECKLIST DATA MODEL
Each set of configuration level of the game is related to Crew, Environment, Operation, or Preparation for pilots of unmanned aircraft only, this is not for general aviation pilots in any format.  There are XX levels
for the user to climb to the top of the knowledge ladder.   
 
### ROOT URL
>    
* All CEOP Topics - LEVEL 1   uast-game-ceop.01.json 
* All CEOP Topics - LEVEL 2   uast-game-ceop.02.json 
* All CEOP Topics - LEVEL X   uast-game-ceop.XX.json 
  
### CHECKLIST OBJECT 
{
"pilotTrainingTopics" = []

"type": 
      [C,E,O,P]
      
"labelTxt": DISPLAY TEXT

            
"difLevel": [1,10] 
}



  
 # TRIVIA GAME MODEL
 A single file download with the game rules, content, and links needed for a trivia game with X levels.

### ROOT URL
>   
* Trivia CEOP - LEVEL 1   trivia.01.json 
* Trivia CEOP - LEVEL 2   trivia.02.json 
* Trivia CEOP - LEVEL X   trivia.XX.json 
        

### TRIVIA OBJECT
{
"parent" = CEOP INDEX

"type": 
      RB=RADIO :: SINGLE ANSWER
      CB=CHECKBOX :: MULTI ANSWER
      
"labelTxt": DISPLAY TEXT
            "ans1": 1
            "ans2": 2
            "ans3": 3
            "ans4": 4
            "ans5": 5
            
"correct": [ans1,ans4] 
}
