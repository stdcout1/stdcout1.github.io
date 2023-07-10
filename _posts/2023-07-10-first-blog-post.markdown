---
layout: post
title:  "First Blog Post"
date:   2023-07-10 11:53:12 -0400
categories: tech
---

## Blog post? WHAT!

Hey there, folks! Guess what? I'm diving into the world of blogging now. Brace yourselves for my random ramblings. Although most of my future blogs won't be as laid-back as this one, get ready to get **serious**.

For now, I've set up two tags: "tech" and "life," so my initial posts will revolve around those topics. Who knows, I might add more tags later on.

(By the way, in case you're curious, this is a Jekyll blog hosted on GitHub Pages using the awesome [no-style-please](https://github.com/riggraz/no-style-please) theme.)

Enough with the introductions. Let's jump right into my first post:

## Leveling up Movie Streaming

So, today I had this wild idea to emulate those big **ILLEGAL** movie streaming platforms. Don't worry, it's not as scary as it sounds. 😄

Streaming movies isn't illegal, just downloading them. Plus, let's be honest, there are plenty of free sites to watch movies online if you really want to.

Now, setting up a service like that would require either manually downloading tons of movies on a server from torrents or streaming the torrent directly to the user.

Obviously, downloading movies to a server would be crazy expensive. So, most services opt for the second option.

But here's the catch: buffering issues galore! The streaming speed depends on the number of peers for the torrent, and that's no fun for the average movie lover.

And what do they end up doing? Paying $10 a month just to watch a limited selection from ONE network. Ridiculous, right?

But wait, there's a secret third option: Real Debrid to the rescue!

Real Debrid is a service that can convert torrents into stable downloads, reaching speeds up to a whopping 1000 MB/s! Mind-blowing, huh?

So, here's the pipeline I'm thinking:

1. The user picks a movie through a cool web front end.
2. The backend searches for a torrent of the movie based on the title.
3. We use Real Debrid (yep, that's the magic) to rapidly download the movie.
4. Voilà! We stream the movie straight to the user.

For this project, I'm planning to unleash the power of Real Debrid, React, and a Rust backend (Rocket). I know Rust isn't a must-have, but it's fun and cool (and hey, I've already written the authentication code using it)! If you're curious, you can track my development progress on the [GitHub repository](https://github.com/stdcout1).

Stay tuned for more updates and exciting content. Thanks for tuning in!

