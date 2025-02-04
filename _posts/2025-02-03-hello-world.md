---
layout: post
title: "hello-world"
date: 2025-02-03 00:00:00 -0000
tag: meta
---

# hello

Hello, world.

Testing showing some Haskell code:

```haskell
around :: Maze a -> Int -> Location -> [Located a]
around maze n loc = mapMaybe (at maze) xys
    where xys = map ((+ loc) . uncurry Location) $ filter filt $ [(x,y) | x <- [-n..n], y <- [-n..n]]
          filt (x,y) = let a = abs x + abs y in a > 0 && a <= n
```