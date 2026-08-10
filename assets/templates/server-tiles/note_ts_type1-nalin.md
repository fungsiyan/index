An accurate type 1 tileset template. To note:
- The black tile at (0, 2) is a blocking (type 22) tile and is used to draw the out-of-bounds of the level.
- Hurt underground tiles don't actually hurt you (at least on client 2.x).
- Desert tiles are identical to "near lava" tiles, but have a different tile type (11).
- None of the special tiles (grass, bush, etc), work on 2.x clients. They are all throw-through (type 22). The client interacts with the level like a type 0 tileset.
