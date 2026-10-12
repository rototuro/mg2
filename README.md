# minigame 2
## Devlog
Write your Devlog here.
1.
One of the issues I encountered as a simple floating point
to double conversion error, which I fixed by appending the "f" suffix
to all the numbers in the switch statement.

2.
So, I see this statement creating what appears to be a new instance of a Color 
object onto the heap using 3 values. I assume that the three values supplied
to the parameterized constructor for Color correspond to RGB or CMY values.
Because "r" is comparatively larger than 0.2 and 0.2, I would assume we would
end up with some kind of red color.

To my knowledge, the period is the member access operator, suggesting that
"color" is itself an attribute of _spriteRenderer, which checks out.


## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
