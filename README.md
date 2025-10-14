# in-class-activities
## Devlog
### W1
Write your W1 activity Devlog here.

Heloo Word

### W2
Create future Devlog sub-headers with the three # symbols, then write your Devlogs below them.
1. Because r, g, and b all represent brightness intensity as decimals between 0 and 1, using int, bool, or string values ​​won't allow for precise control of color gradients.
2. Because the number of bounces is always an integer, there won't be a situation where there are 1.5 bounces.
So, using int for counting is most appropriate. float is too precise, bool can only represent true or false, and string is text and can't perform mathematical calculations.
3. You must add f after each float value; otherwise, an error will be reported.
## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 

W3
#16
The input is float sanityPercent, and the output is set to void
A class is like a "mold," and a component is made from it. Member variables are its parameters, such as color and size. Methods are the actions it performs, such as turning it on and off, or changing its color. The ball becomes brighter the more it bounces because each collision multiplies its color/luminescence by a factor greater than 1. The more collisions occur, the brighter it becomes.