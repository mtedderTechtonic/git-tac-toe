# git-tac-toe

## We're going to play a timeless classic to continue developing our understanding of git and version control fundamentals

To start the game, you'll pair up with someone from your cohort.  After one of you creates a **`fork`** of the base repository, you'll both want to **`clone`** that forked version and open it up in your editor.  

From there, each player should create a branch titled with their name.  You can do this by using git flow's ```git flow feature start <FEATURENAME>``` or traditional git commands (see [Git Flow vs. Git](https://gist.github.com/andrewdwatters/ab3859079f139a31211308d4ac774813) below). 

Now, decide who will go first and start playing the game by taking turns entering either an **X** or an **O** in the ```<div>``` tags with numbered id's.  



### Finishing your turn

When you've made your move, you should ```commit``` your changes, ```push``` to your remote repository (ie: origin master) and submit a **pull request** to merge your changes into **develop**, assigning it to your opponent.  

If your move is valid and there are no issues, your opponent should approve your **pull request** (even if they don't like it!).  


### Staying up to date

After your opponent makes a move, they'll submit a **pull request** and assign it to you, asking to merge their changes into **develop**.  Once you've merged their changes, you'll need to incorporate them locally before taking your next move with ```git pull```.  Reference the attached documentation if you need help figuring out how to do this.  


### When the game is finished

Test **develop** and then merge it into **master** and submit the link to your completed repository to the instructional team. 

### Resources
* [Git Cheat Sheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)
* [Git Flow vs. Git](https://gist.github.com/andrewdwatters/ab3859079f139a31211308d4ac774813)
* [Git Flow Cheat Sheet](https://danielkummer.github.io/git-flow-cheatsheet/)
* [Git/Source Control Flashcards](https://www.goconqr.com/en-US/p/16397179)
