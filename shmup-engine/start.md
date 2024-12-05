# Start

Date: 12-4-2024

---

"Oh, this is an interesting quirk! It's an interesting quirk because the developer implemented it this way, not because the quirk is inherently interestng!" 

---

That is the ultimate feeling we want to capture with this shmup engine. 

My claim is that if you provide a powerful enough shmup editor, and an granular engine to boot (full replay, rewind, savestate, etc.), shmup "theory" will evolve to a new level. 

Well, that might be too strong. At the very least, it might encourage people who enjoy shmups to practice harder, more unique patterns. 

And the search space isn't exhuasted by any means ; just look at Zun's patterns. A lot are kinda rng vomit garbage, but a lot are great. For example, Nue's falling red orb non is a really creative spell. 

# Architecture

The idea is at its core, a shmup language standard, and an engine specification standard. The engine doesn't inherently do visuals - it will be architected in such a way that there will just be event records that it spits out, and it's the job of whatever visual renderer there is to render the specific things. 

A naive implementation should be so simple and robust that you could literally plug and play with it within multiple different applications , wtihout having it break. 

It does not have to be some super optimized thing - at first I was thinking that underlying we could make it target a VM or whatever, but just making the standard, a standard, is good enough. 

# Monetization

The engine and standard are all going to be open source, and ideally any kid can pick it up. So basically, this is relegated to the world of passion project. 