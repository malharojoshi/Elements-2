elements{
characters{
packman,ghosts
ghosts = 3 ghosts
}
story{
pacman = guard
ghosts = thief
}
goals{
catch all the theifs
}
rules{

1. control over Packman
2. passage will open and close within intervals
3. 3 power switch
4. 6 coins
5. if they collect all the coins the power switch will be disabled
6. time limit is 2 minutes
7. pacman loses a life if {1. the ghosts collect all the coins 2. if the time limit is crossed}

   }
   balance{}
   adaptivity{}
   chance{}
   skill{}
   feedback{
   score for player{
   if pacman eats ghost then score+1
   }
   score for ghost {
   if ghost collects the coin then score+1
   }
   }
   }
