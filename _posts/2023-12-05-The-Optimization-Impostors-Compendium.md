---
title: The Optimization Impostors' Compendium
date: 2023-12-05 21:58:59 -0500
categories: [Projects]
tags: [optimization]
mermaid: true
image:
  path: /assets/img/2023-12-05-The-Optimization-Impostors-Compendium-thumb.webp
  alt: Image by DALL·E showing text-to-image aberrations increasingly rare in early December 2023.
  lqip: /assets/img/2023-12-05-The-Optimization-Impostors-Compendium-thumb-low.webp
---

In July, after six years, I left AMPL Optimization, Inc., the team behind the AMPL algebraic modeling language. Mathematical programming tools like AMPL, GAMS, JuMP, PYOMO and others are typically used:

- to teach Operations Research, Industrial Engineering, Applied Math, etc., and ...
- to build fast optimization models at the heart of large real-world applications.

We sold the language (its interpreter, technically) to teams struggling to implement large problems with other tools: the slowness of straight-Python implementations being the most common issue we saw in recent years. In most cases, however, we did the bulk of the model implementation for our customer: "give us your broken thing, we'll implement it our way, and if it works you buy our thing".

I took point on scoping these little per-customer mini-projects and delivering working models ... "making sales through saves". Especially in the early years I leaned heavily on our ridiculously capable team for technical help - PhDs, the lot of them, at the intersections of math and computer science. Later on I could ship many models myself, but it is beyond lucky to be the dumbest guy in the room learning from brilliant people how to do hard things. 

My luck stretched unreasonably further though, which no doubt had a positive effect on my learning curve: I had a window onto the actual optimization practices of airlines, hedge funds, power grid operators, ride-share companies, coffee giants, agribusinesses ... many of whom addressed complex problems through some combination of discrete methods and outright hacks. On customer sites, I met *real cows*, walked through seas of seedlings grown for Walmart and Home Depot and met so many wonderful people who make our world work. Optimization is magical, and its tribe has much goodwill and love.

When a problem with real-world stakes hits a computability bound, however, optimization also gets *super* interesting. Custom hardware builds, low-level manuevers, whole-of-toolchain re-engineering ... heaven for geeks like me, and maybe you too :)

And now I am out. (It was time.)

Having left AMPL and sold all my AMPL shares, I am presently not affiliated with any player in the optimization marketplace (Gurobi, IBM, Llamasoft/Coupa, NVIDIA, etc.). This frees me to discuss the construction of optimization toolchains without a commercial agenda, and with a focus on the structure of the chain (app) itself, rather than on just one tool.

Obviously I cannot share actual models I worked on, and that suits me since building new models for this Compendium will be a blast. What methods and lessons I might have to offer can be generalized from specific experience and shared. And, dammit, I intend to have some fun with this! There is a thrill unique to optimization that I want very much for more people to feel!

Documenting what the best practice of late 2023 in the pockets of industry I have visited might hopefully be useful to some folks. In particular, I want to  the Imposter - the person who does not feel they should be on the spot for making this thing work, but are. I 


moreover I feel that I owe it to the optimization tribe - all those compassionate insiders who made me, an imposter, one of them - to document the best practice as I see it, in late 2023.



Optimization Impostor's Compendium, at [opt-compendium.com](https://opt-compendium.com)



Disclaimers:

I am not a PhD in any field remotely relevant to high-performance computing, optimization or mathematical modeling. My experience is therefore practical and not academic. I have love and respect for algorithm researchers and OR/IE scholars and have learned much precisely from them.

AMPL is the optimization language I know and love, and I would not feel qualified commenting on how to get something tricky done in another language, so 

