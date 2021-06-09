# Kerd
  
  ## Rules
  
  1. Infiltration
  - At the start of the game, each player choose an enemy piece as infiltrator.
  - The King, the Queen, Rooks, and Scouts cannot be chosen as infiltrators.
  - Infiltrator pieces can only be revealed after either player has checked his opponent.
  - The turn ends after a player reveals his infiltrator piece.
  - After an infiltrator piece is revealed, it changes its color and its side. 
  
  2. Board Regions
  
     a. Water
     
        - Pawns can be moved by only one square on their first move.
        - A piece that in this region can't capture a unit on land or water regions, if there are air tiles between them. Scouts, Towers, and the Queen are not affected by this rule.
        
     b. Land
     
        - Pawns can be moved by one or two squares on their first move.
        - A piece that in this region can't capture a unit on land or water regions, if there are air tiles between them. Scouts, Towers, and the Queen are not affected by this rule.

     c. Air
        
        - Pawns can be moved by one, two or three squares on their first move.
        - A piece that in this region can capture a unit on any region.
     
  
  ## Pieces

  1. Pawn
     
     - Moves one square forward vertically.
     - Captures one square forward diagonally.
     - Can make an enhanced move depending on its region on its first move.

  2. Commander Pawn
     
     - There are 2 of these in front of the King and the Queen.
     - Moves and captures like normal pawns.
     - Can attach on a pawn around and move with it.
     - If the attached pawn can't move as far as the commander pawn, they can only move as far as the attached pawn does.
     - If a pawn is captured on any square around this piece, the commander pawn can recapture on that square. 

  3. Bishop (Rename)
     
     - Moves and captures diagonally to any square as long as it follows the region rules.
  
  4. Scout

     - Moves and captures like bishops.
     - Is not affected by regions as mentioned in the rules.

  5. Hussar

     - Moves and captures two squares vertically and one square horizontally, or two squares horizontally and one square vertically, or three squares orthogonally.
     - If it jumps over an enemy piece, it can't move or capture three squares orthogonally.
  
  6. Jumper (Rename)
     - Moves one square to any direction.
     - Captures on one square forward diagonally or one square forward vertically.
     - Can jump over a friendly or enemy piece if there is no piece behind it.
     - Is affected by regions. This piece's jump ranges are [0, 1, and 2] on [water, land, and air] respectively.
     - After the jump, it always lands on the square next to the piece that it jumps over.
  
  7. Tower (Rename)

     - Moves orthogonally to any square.
     - Is not affected by regions as mentioned in the rules.
    
  8. Queen

     - Moves and captures orthogonally or diagonally to any square.
     - Is not affected by regions as mentioned in the rules.

  9. King

     - Moves and captures one square orthogonally or diagonally.
     - When a player capture oppenent's king, the game is over.
