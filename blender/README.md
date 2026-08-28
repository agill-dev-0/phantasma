#Phantasma
##An apparition that remembers the Greek myths
##Ask about gods, heroes, and the stories in between

##Blender

###Design Notes:
 Phantasma is an apparition that communicates via a medallion. It answers all questions about Ancient Greek Mythology and narrates the tales. Design a 3D medallion with Greek inspired design symbols. There should be a relief skull in the centre with a separate jaw so that the jaw can be moved independently of the head in order for the skull to speak. 

###Design Spec:
3D PBR bronze medallion with four decorative rings on the outside.
1) Egg and dart
2) Bead and reel
3) Meander
4) Beads alone

Low poly skull in the center of the medallion.

Laurel wreath around the skull.

Greek inscription at the bottom of the skull - translation of phantasma. There should be enough gap for the bottom part of the skull to open during talking.

###Animation Architecture: 
 Keep the rings, skull, jaw, laurel as separate objects so that they can be transformed natively without adding the weight of shape keys or bones or keyframes to the gLTF so that it stays small and loads fast on mobile.
