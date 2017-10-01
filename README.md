# product-board
Main product board for MCT1

Assumption:
  - newly diagnosed T1 patient in hospital for 1 week

Outline:
* lvl 0 - intro/tutoral to minecraft
* lvl 1 - get T1 by getting struck by lightning
  * start in a village
  * descover path through "Thunder Plains" where the are advised to "Beware of Lightning Strikes"
  * inevitably they get struck by lightning
  * when they get struck by lightning, they get T1
     * half food
     * high BGL
     * bars appear on the screen, with no explaination
  * they wander around, eating has no effect,
  * conditions deteriorates, 
    * they experience the adverse symptions
    * start randomly casting spells
  * lose consciousness
* lvl 2 - intro to managing T1
  * wake up in a magic castle
  * you've got magic powers! Now learn how to master them!
  * MP3s playing from PlayApp, triggered of region enter
    * user messages to make sure 
      * playapp is open
      * sound is on 
* levl 3-7 - go on a Quest 
* lvl final - choose to be cured, of keep it with yr magik powers?

### Aux development
* videos
  * development vids
    * tell the of making MCT1
    * audience: 
      * stackholders
      * developers looking to code Magikcraft plugins
    * coding/building MCT1
    

### TODOs
##### Sprint 1
* create a basic world - random generated
  * set spawn in village
  * create `thunder desert`
  * create `lightning strike` on enter region
    * enable T1 plugin for player
    * set player state
      * health
      * food
  * create "onLoseConsciousness" event
    * teleport them to lvl 2 start
  

##### Sprint 2
* NPC Plugin

  
