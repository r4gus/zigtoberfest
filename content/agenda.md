---
{
    .title = "Program",
    .date = @date("2020-07-06T00:00:00"),
    .author = "David Pierre Sugar",
    .draft = false,
    .layout = "page.shtml",
    .tags = [],
}  
--- 

## Zine: a Static Site Generator Written in Zig

After years of using other SSGs I decided to write my own in Zig. In this talk I will showcase its most interesting features and what plans I have for the future.

[https://zine-ssg.io](https://zine-ssg.io)

### Speaker: Loris Cro

VP of Community @ Zig Software Foundation

- [https://kristoff.it](https://kristoff.it)
- [https://zig.show](https://zig.show)
- [https://softwareyoucan.love](https://softwareyoucan.love)
- [https://zine-ssg.io](https://zine-ssg.io)

## rayzui: a zooming user interface (ZUI) library

rayzui is a raygui-style ZUI immediate mode zoomable user interface mini widget set for building ZUI applications on raylib.

### Speaker: Martin Weber

I'm a didgeridoo player and I spent more than half a life earning money from coding in various environments. I like old.

## Approaches to Memory Mapped I/O

In embedded systems programming I/O devices are controlled through memory mapped registers - memory locations that act as messaging channels for the hardware peripherals. Different programming languages offer various tools and techniques to solve this deceptively simple problem. I'm going to explore and compare how languages like C, Rust and Zig fare in this aspect. 

### Speaker: Mattia Maldini

I'm an embedded systems developer from Bologna, Italy. I have a Master's degree in Computer Science and almost 10 years of experience in the field. I'm also a enthusiast for everything that involves programming languages, from Logic to compilers. I've written a few [blog posts on Medium](https://medium.com/@maldus512).

## Exploring properties of constraint programs in ZIG

Only few people are familiar with the paradigm of constraint programming, which is unfortunate! Unlike imperative programming, where you explicitly define a sequence of steps to achieve a result, constraint programming focuses on specifying the desired properties of the result. This approach often allows us to formulate algorithms in a much more concise way.

We will explore constraint programming through the lens of CHR (Constraint Handling Rules). Therefore, I will provide an embedding of CHR into the ZIG language, and we will use this embedding to examine some example CHR programs and their properties. We'll pay particular attention to confluence and the completion algorithm, and we'll discuss the additional benefits that confluence automagically provides.

We could also look at some rule based formalisms and how we could embed them into CHR (and embedding inside an embedding lol). But there's probably not enough time for that, and this is definitely a big enough topic to deserve its own talk (maybe at the next Zigtoberfest :D)

### Speaker: Lukas Pietzschmann

I'm currently studying for my master's in CS at Ulm University, where I also got to know the topic I want to present.
