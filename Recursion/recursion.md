Recursion is when you define something in terms of itself. Has anyone ever used the word you wanted defined in the definition that they gave you? "What is a computer?" "It's something that computes things." This would be a recursive definition.

When we talk about recursion in computer science, we are talking about a function that calls itself. This technique is especially adept at some problems because of its ability to maintain state at different levels of recursion.

While recursion can make the code very simple for some problems, it inherently carries a potentially large footprint with it as every time you call the function, it adds another call to the stack. Some problems therefore are better solved in a slightly-more-complicated-but-more-effecient way of iteration (loops) instead of recursion.
