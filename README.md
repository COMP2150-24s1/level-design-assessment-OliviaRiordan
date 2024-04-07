# COMP2150  - Level Design Document
### Name: Olivia Riordan
### Student number: 47715766 

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
What does the player learn? How does your encounter and broader level design facilitate learning in a way that follows good design practice?

### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 

### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Checkpoints
I chose to have checkpoints as the first mechanic for the player to encounter so that they don’t need to repeat the jumping practice if they die in the acid that comes directly after.  

### 2.2. Acid
I made the acid the first dangerous mechanic that the player encounters because it doesn’t go above the ground like the spikes and does not outwardly attack the players, making it my preferred introduction to dangerous elements in the game.

### 2.3. Health Pickups 
I put the first health pick up after the first acid encounter so that the player wouldn’t be too harshly punished if they didn’t get through the encounter on their first attempt. Furthermore, it would put the player in a more confident position moving forward as they wouldn’t be as concerned with the number of lives remaining.

### 2.4. Passthrough Platforms
I wanted to introduce the passthrough platforms next because I thought that they would a useful element to include as the player progressed through section one without dropping through holes in the ground, making the level feel more complete.

### 2.5. Moving Platforms
Having the moving platform next allowed me to introduce switches and how they work while also being able to have the first opportunity for the player to decompress after what they’d done. 

### 2.6. Spikes
I put the spikes here to reintroduce the player to danger after the moving platform without having the ‘enemy’ attack the player. It also allowed for some more precision training with the jump button.

### 2.7. Weapon Pickup (Staff)
I put this next as I thought the player would be ready to handle a weapon and how it can be used. Furthermore, it would also allow me to start introducing breakable columns as a way to segment between encounters.

### 2.8. Chompers
I introduced chompers at this point so that the player could attempt combat with the staff and learn how to use it to defeat an enemy. It was also close enough to the staff being introduced that the player would be able to connect the staff to the chomper.

### 2.9. Weapon Pickup (Gun)
I introduced this here so that the player would have a way to protect themself against the spitter since it would.

### 2.10. Spitters
I introduced this enemy type last as I thought it was the most dangerous and to keep with the dramatic arc and not wanting to overwhelm the player too soon, I chose to introduce it now.

### 2.11. Keys
I introduced this last as a way of almost congratulating the player for completing the tutorial section of the level, also due to only needing three, I wanted them to mark the end of each section and have them feel rare.


## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.
When designing my game I thought that it had a balance between high and low intensity areas, but also that it would be take around the correct amount of time to complete. Once I build the level within Unity, however, I found that neither had been achieved. I was able to complete the level in three minutes and I didn’t feel like the intensity changed enough throughout. Hence I employed some iterative design practices to try fix this issue. To do this I added two encounters that involved basic parkour. Additionally, there was a section where you could pick a path, which I had to change to fix the time disparity between them. 

My goal with the parkour encounters was to allow the player to practice their movement skills within the game without continuing the tutorial. Furthermore, the lack of enemies means that the player would not need to focus as heavily on the game allowing them to think about what they had experienced. This also allowed me to add more time to the duration of the game.

To plan these out I drew up extra sections for the level map so that I could visualise how much space I would need and whether or not the different jumps would be realistic before putting them into the game. This also allowed me to gauge if parts would get repetitive or and how time consuming they maybe. Furthermore it allowed me to make sure that I wasn’t putting so much parkour in that it broke out of the dramatic curve.

Originally I had an option to choose a parkour section or a combat encounter, however the enemies were a lot easier to kill than I had originally anticipated. To fix this disparity between the parkour and the combat I decided to force the character to do both sections and also add some extra combat to make the game longer.

I think that some of the later combat encounters could benefit from some more iterative design as they don’t feel as challenging as I was hoping that they would. For this I think some paper prototyping would be useful and possibly using an enemy spawner so there aren’t as many to attack at once, whilst still having a lot of enemies to defeat.


## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: ChatGPT
**Nature of Use** Finding relevant design theory.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to try and find some more relevant design theory that I could apply to my game. After googling them, however, I found most of them were inaccurate, and some didn't exist. One theory mentioned, however, was useful, and I've incorporated it into my work.

### Tool Used: Example
**Nature of Use** Example Text

**Evidence Attached?** Example Text

**Additional Notes:** Example Text


