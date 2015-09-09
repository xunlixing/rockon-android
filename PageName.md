## Headset integration ##

Loads of people report erroneous behaviour of a number of headsets, specially bluetooth ones.


## Album list sliding window implementation ##

The current implementation puts all album covers in memory so that scrolling is smooth. If the number of albums exceeds 30?, the album covers are stored slowly begin to degrade quality. If the number of albums exceeds 80? then the albums are not stored in memory.

  * the goal is to implement a memory pool of album covers with only a limited number of covers (say 30?) - and then manage this memory pool when the list stops scrolling. **Very important** is that this memory management does not affect the smoothness of the list scroll.

## Faster start-up ##

## Faster rotation ##

## Classic controls? ##

## Synchronization between UI and service components ##

## Previous song functionality ##

## Code Clean-up / Code Comments ##