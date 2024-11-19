---
layout: default
title: Blog/Writing
order: 3
---

# Introduction

I figured it'd be good to contextualize my blog a bit. My background is in math and physics, but my current research interests have called for learning a ton of ecology/evolution/paleobiology recently, so many of my posts might touch on those fields. I am hoping to also use this as a way to stay in touch with the mathematical side of life, though. And I always welcome comments (via email until I change platforms or figure out how to add blog comments in Jekyll) if anything I say is inaccurate or could be clarified—learning is a huge reason why I write, after all.

<!-- # What, and why, write?
I think it's good for a blog to have a sort of "mission statement" so you dear readers know what to expect if you stick around:

> My goal in this blog is to share some of my love for both the natural world and its study.

Here are the types of posts I do (or plan to do):
- **My New Favorite Organism (MNFO)**: MNFO is inspired by the "Creature Feature" column of my graduate group's offical blog, [*The Ethogram*](https://theethogram.com/category/creature-feature/), but here I take a bit more liberty in talking about non-behavioral aspects of organisms as well as non-animals.
- **EvoBites** (Name pending): EvoBites (or whatever I decide to name it) is where I will talk about concepts or methods in biology. I am inspired to write these because teaching a topic is a great way to learn about said topic. This also means that I am learning while writing some of these, and they may fall outside of my expertise. I hope that my citing sufficient sources will be enough to get you to believe me, or at least understand my thought process enough to tell me why I am wrong!
- **Lessons from Nature**: Lessons from Nature is a column where I describe some natural phenomenon and discuss the lessons it can teach us. This could be an animal doing something cool that teaches us how to do that same thing, or it can be something more abstract. This is the column that plays most to my research, since I am all about learning about physics through organisms and organisms through physics.

Let me know via email if you think of anything interesting that I should take a look at, even if it doesn't fit under one of these labels! -->


<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>