# monocular-depth-estimation
research notes
monocular depth estimation is the process of estimating how far objects are from a single camera u
single image usually doesn't give us enough info to determine actual distance

ai models can learn visual cues such as 
- perspective: closer to horizon = farther
- apparent size: look smaller as their distance increases
- occlusion: partial blocked which gives us clues
- scence context: patterns about other relative obbject sizes 
not always reliable: ex. toy car on desk mimicing car on road, scale ambiguity

focal length = how large an object appears in th image at given distance
instead
videos can give us additional info, how fast an object expands as we get closers
time to collision (TTC) without knowing actual metric distance or our speed

TTC = apparent size/rate of expansion
research questions to revisit

can autonomous robot navigate safely using visual motion cues without reconstructing 3d model of its env
