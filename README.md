# PygameGameCamera
A module for creating simple game camera objects in Pygame.

A GameCamera captures a part of the given World object in the given position and produces a pygame.Surface object of the given size.

You can design the World class yourself with these attributes:
- rect - a pygame.Rect object
- surface - a pygame.Surface object
- objects - a list of objects the camera can follow (focus on)

Some uses of this module:
- a camera that follows a moving object (like player)
- multiple cameras focused on different objects and showing different displays (multiplayer game, cutscenes etc)
- turn cameras on/off, make them jump to a specific location
- bind keys to the camera's move method
- detect which camera's display the cursor is positioned over using the camera's mouseover method (build complex interfaces)
