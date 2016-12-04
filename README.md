# css-animation

This is a simple CSS animation function that I have used for multiple projects.

As I stated in all my other repositories - The first thing that you will probably notice is that it is HEAVILY commented.  This was intentional (yes, even to this extreme degree), mostly just for myself.  I am still fairly new to coding, and multiple times in the past when I have gone back to some of my previous work I would always have a hard time understanding what my code meant.  So along with relentlessly detailing everything that I was doing in the code, I also tried to capture the mindset that I had while I was coding it (or rather, why I coded it the way that I did).

This is also has the added benefit of helping to remember this information without the need for comments - sort of like when you write something down to remember it, and the act of writing it down is what helped you remember it.  With the only downside being the time taken to write the comments (since minifying removes all of the extraneous content), I saw no reason not to.

I would think that most of this code is fairly straightforward, with the only exception being the -Math.abs parts.  I tried multiple ways of writing this, including using operator objects (!!!!!!!!!see: operators.js!!!!!!!!!!) to perform the math that was needed.  In the end, I just liked this method better.  This method seemed cleaner and less convoluted than the other methods that I tried.

I also tried a version that added in an optional second operator function that would be performed on/after the first operation (for things like setting an opacity, which would require a division by 10), but again it seemed overly convoluted and I ended up just using different functions !!!!!!!!!!!(see: scroll.js and fade.js)!!!!!!!!!!.  Possibly in the future I will write one that combines all of those functions into one function, just to have to either play with or if it is needed (sort of like I did with my !!!!!!!!! https://github.com/S1lentEchoes/js-bounce-animation and bounce-alternate.js!!!!!!!!!!!!).

I think that about covers it, any more code explanations that may be needed can easily be found inside the file's comments.  I have included both the normal version, and the minified version.

I have created repositories for other files that make use of this file (there were a lot more files that made use of this function, but they were project relevant and not extensible for other uses) -

1. https://github.com/S1lentEchoes/js-bounce-animation
2. scroll.js
