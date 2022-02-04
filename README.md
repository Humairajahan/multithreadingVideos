# multithreadingVideos

This repository aims at 
- collecting frames from 4 separate videos using multithreading
- merging the frames using numpy according to the image provided in the "task objective"
- resizing the merged frames from (3840,2160) to (1920,1080)  
- creating one final video using opencv

If faced with a memory allocation problem, it would be advisable (if the memory allocation problem cannot be solved) to save the frames during the multithreading and then calling them again to merge them. 
