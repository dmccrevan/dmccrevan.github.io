+++
title = "Week 2 of Recurse"
date = 2020-08-21
[taxonomies]
tags=["Recurse", "Learning", "Compilers", "Functional Programming"]
+++

Today marks the end of my second week at Recurse. What an awesome time it has been so far! This past week was open-source week at RC so I was able to attend
in a few open source workshops that were very fascinating. This past week also gave me a better perspective on what I am more interested in focusing on
and how to mold my project goals to fit that. 


My days have consisted of attending the functional programming group meetings in the morning, reading through [Engineering a Compiler](https://www.amazon.com/Engineering-Compiler-Keith-Cooper/dp/012088478X), working on my [Rust priority executor](https://github.com/dmccrevan/priority-executor), and attending the compiler
study group meetings. Most of my time this week was dedicated to the Haskell exercises for the functional programming material and the reading material for the compiler group. 
Even though I am only working on my priority executor from my original project goals, I like the way my experience has shaped into so far. I am starting to appreciate the
technical textbooks a lot more than I did during my time at college. 


The way I see myself moving forward with my goals is by focusing on my rust project as well as starting only one other project that will be an application of my learning
in FP & compilers. A few peers of mine have discussed writing an arithmetic compiler in Haskell, I like this idea.

I am very excited to see what this next week holds!

~ Dan


P.S. If you're into Haskell & monads, here's a funny little code snippet:

```
toMaybe :: Int -> Maybe Int
toMaybe 0 = Nothing
toMaybe x = Just x

test = toMaybe <$> Just 0
```

Then invoke `test` to find the funny result, at least in my opinion it is
