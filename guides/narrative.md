# Narrative

Following from tutorials such as *Vim Adventures*, RustQuest aims to wrap its educational elements in a fantastical narrative, in which the components of Rust are each analogized to some part of a magical world in order to help make them distinct and comprehensible to students unfamiliar with the history and construction of computers and programming languages.

Thus functions are analogized to spells, files to spellbooks, libraries to... libraries, the compiler/borrow checker to a magical familiar, and so on. 

The choice to analogize programming to magic is intentional, because software engineering is the closest thing in our real world to the magic of fantasy: a means by which strange words in arcane relation to one another produce novel effects, which can be learned through time and effort, and in which there are always deeper, more complex insights to be gained from understanding the work of those who came before.

## Outline

The broad outline of RustQuest's narrative should proceed in three stages from an introductory premise:

### Premise

Long ago, in a world of magic...
War raged among the wizards.
Their enemy was the Dark Lord Malloc, a powerful wizard who corrupted memories.
They fought Malloc in many battles, and at last defeated him...
But Malloc had grown too powerful, and too full of memories, to die.
The wizards hunted Malloc's spirit across the land, and found it within a newborn child.
The wizards argued about what to do, for the power of Malloc was terrible indeed. 
Some worried that Malloc might one day return; others worried that a child with Malloc's power would endanger everyone, even themselves.
An archmage, who has been Malloc's friend once, brought the solution: they would seal the dark lord's power deep in the child's mind, and teach them the ways of safe magic.
The child would be safe from Malloc's corruption, and one day would use that power for the good of all.
This is their story, their...
RUSTQUEST!

### The Cradle of Magic

This section concerns the early days of the protagonist learning magic, in the safety of the archmage's tower and with their personal direction. This coincides with the sections of the pedagogical roadmap teaching keywords, syntax, primitives, and rebuilding simple parts of the standard library.

This section ends when the archmage succumbs to the lingering curse of Malloc, and willingly enters a dreamless sleep in order to halt the progression of the curse. Before entering this sleep, they give the protagonist their quest: to develop their safe magic and enter Malloc's extradimensional vault of memories (external test server) to retrieve the archmage's memories using their true name (private key). 

At this point, the protagonist also gains the archmage's spellbook, which contains the standard library and thus transitions out of the `#[no_std]` environment.

### Adventures

This sections covers the longest part of RustQuest, in which the protagonist, having learned the fundamentals of safe magic and having received the last request of their mentor, explores the world, helping others, gathering allies. In this time, the student learns more advanced programming concepts and Rust idioms (as well as some common non-standard crates).

This includes an introduction to `unsafe` code, represented by the sealed spirit of Malloc surfacing and giving tutelage. Malloc and his power cannot be disentangled from the protagonist and cannot be disavowed. It is necessary, but must be treated with caution.

### The Magnum Opus

This section is analogous to the final project from the Rust Book. It is the shortest section and the one which brings all the concepts learned earlier to fruition.

Having completed their other adventures, the protagonist gathers their allies and returns to the archmage's tower in order to construct a magical portal to enter Malloc's vault of dreams. 

This consists of creating their own crate using what they've learned over their adventures. In addition to building on past concepts and bringing them together, we also teach good code organization and cargo. 

When the final task is complete, the archmage awakes from their slumber with all their memories, and all ends well.

## Tone

The tone of the lessons should be family-friendly and suited to children of age 8 and up. This does not require saccharine or twee aesthetics--adults too often forget their own childhoods and that children are eager to engage with the world as adults do--but it does require some distance from mature topics. This should be a resource that reasonable parents can give to their children and teachers to their students without worrying about the content inside.

## Themes

It is important to the themes of RustQuest that the narrative wrapping around lessons not be the standard kind of fantasy adventure fiction (personal enjoyment of that kind of fiction aside), which centers a glorious fight against some enemy and the ultimate triumph of good over evil. Rather, we should center stories which better align with what Rust is actually used for: building, aiding, and illuminating. 

The acts through which the protagonist proceeds towards the conclusion should be the acts of constructing systems oriented to solving the problems of others, improving their lives, and bringing knowledge and clarity.

This is most important in the finale: the final project, the protagonist's magnum opus, is not a final battle against the villain in which evil is vanquished. It is the act of creating, through effort and ingenuity, the means to return a loved one to waking life. 

Real world problems are not, as a rule, solved by hitting someone with a big stick repeatedly. This is particularly the case for problems solved through software engineering, which is not remotely analogous to a big stick. Rather, solutions are architectured, built, shepherded, and nurtured, in order to improve the lives of concrete human beings.

We focus on these kinds of stories to ensure the themes of RustQuest are consonant with the actual, worthwhile projects the student will one day use Rust to bring to fruition. We start as we mean to go on.

