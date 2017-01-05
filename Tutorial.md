#How to do the POC

1°) Download Unreal Engine

2°) Create new blank project (Blueprint)

3°) Create a new sphere with big enough dimensions (20, 20, 20) gives a pretty nice feeling.

4°) Import the texture (equirect.jpg)

5°) Drag&Drop it on the sphere

6°) Edit the newly created material

7°) Multiply TexCoord by ConstVector2 (-1, 1)

8°) Apply the result to UV

9°) Connect right node on main component to "Emissive Color"

10°) Tick "Both sided" on Material properties

11°) Place Camera in the sphere (middle)

12°) Click on "Play On VR"

13°) Enjoy
