# Hello there 👋

My internet name is douira.

I recently completed my Master's of Computer Science at the [University of Lübeck](https://www.uni-luebeck.de/universitaet/universitaet.html) and **am now looking for a job**. Let me know if you have something exciting! I'm interested in algorithm development, computational geometry, computer graphics, complexity theory, generative art, game technology, and interface design. Most of my work is in either Java or Typescript.

## My Projects

- My Master's thesis: **Implementation and Analysis of Geometric Algorithms for Translucency Sorting in Minecraft**
- [Ongoing contibutions](https://github.com/CaffeineMC/sodium-fabric/pulls?q=is%3Apr+author%3Adouira) to the Sodium Minecraft optimization mod
- The Resolution Editor is a document management and synchronized editing software for use at MUN conferences like [MUNOL](https://munol.org/). It is also used at RIMUN and MUNoH.
- [glsl-transformer](https://github.com/IrisShaders/glsl-transformer): A GLSL program transformation Java library based on ANTLR 4, used in [Iris](https://github.com/IrisShaders/Iris/).

## Master's Thesis

_Implementation and Analysis of Geometric Algorithms for Translucency Sorting in Minecraft_

<details>

<summary>

<b>Click to read the abstract</b>

</summary>

Ordering translucent quadrilaterals (quads) by descending depth produces a correct image with alpha-blended translucency. Generating such an order efficiently with a moving camera is challenging in general. Since translucency is common in computer graphics, a multitude of techniques have been developed for it, but none is universally optimal. This work implements quad-based translucency sorting in Sodium, a Minecraft modification focused on rendering performance. A sort order is obtained by topologically sorting a visibility graph over the quads with respect to a polytope of view points. However, this algorithm's quadratic runtime and potential for sort failure when being approximated limit its suitability to static sorting. Axis-aligned multi-partition trees without quad fragmentation can be used instead. They are efficiently built with a projected interval scanning algorithm and generate dynamic sort orders 60 percent faster than sorting quads by distance. Together, these techniques improve visual correctness and provide a performant translucency sorting system. Unaligned partitioning, although not necessary for Minecraft, fully exploits partitionable geometry and lends itself to interpretation in parameter space. It is given a polynomial upper bound and options for transferring a lower bound from linear constraint solving.

</details>
<br>
You can download the [thesis text](/assets/document/douira-master-thesis.pdf) and accompanying [presentation](/assets/document/douira-master-thesis-presentation.pdf).

If the math is actually wrong somewhere, that would be good to know but so far nobody has noticed any issues. If you want to cite this in your own scientific work: you probably shouldn't, because it's not a journal-published work, but please get in contact with me in that case. Usual copyright applies. Let me know if you have any questions!

The text serves documentation of the implemented theoretical concepts, but doesn't go into many implementation details. These two PRs [#2016](https://github.com/CaffeineMC/sodium-fabric/pull/2016) [#2352](https://github.com/CaffeineMC/sodium-fabric/pull/2352) are the implementation of translucency sorting in [Sodium](https://github.com/CaffeineMC/sodium-fabric).

#### Errata

Figure 5.2 and the associated caption wrongly state that no instances of aligned unsortable yet non-intersecting geometry exist. Aligning the quads in Figure 2.2 to the axes if they are sufficiently long seems to produce a counter-example. This has no effect on other statements made throughout the text.

## Links

- [My GitHub Profile](https://github.com/douira/)
- Contact by email: `me at-sign douira.dev`

## Donate

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/A0A27Y8FJ)

## This page

...is pretty bare bones. I'll add some more to it and make it nicer in the future. Jekyll is very cool though!
