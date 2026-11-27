# Kenneth J. Weber

Can we tune this prototype into a product, or do we need a different design? I like building the smallest model, test bench, or experiment that can answer that question while there’s still time to change the design.

## Computer vision demo

[Repository](https://github.com/kj-weber/Kens-Computer-Vision-Demo) · [Pipeline source](https://github.com/kj-weber/Kens-Computer-Vision-Demo/blob/master/steady_core.py)

In this Python demo, camera capture, feature processing, and display run in separate processes. After rendering a frame, the display process clears the backlog in its input queue. For a live preview, I’d rather drop frames than give someone a faithfully rendered view of what happened a second ago.

## How I build software

Sometimes I write a small version of an algorithm before reaching for a library. Usually the library wins. The exercise is how I find out which assumptions I’m handing over to it. It’s also why I wanted to learn on a manual mill and lathe: I like understanding what I’m asking the machine to do.

I think coding agents will make it cheaper to try a design. Deciding whether the design worked is still engineering. When an agent says it’s done, I want to be able to rerun the task from the same starting state and check the files or behavior it actually changed. I don’t need two runs to take the same route. I need a check that can tell me whether both got to the right place.

I have a soft spot for the small failure everyone has learned to work around. If I can reproduce it and fix it in place, I’d rather leave the next engineer a test than another caveat in the docs.

## Paper and patents

- [Multi-directional image stitching for mobile robotics](https://ieeexplore.ieee.org/document/9649791) · IEEE, 2021 · first author
- Co-inventor on three GM-assigned U.S. patents: [12,293,542](https://patents.justia.com/patent/12293542), [12,715,255](https://patents.justia.com/patent/12715255), [10,953,712](https://patents.google.com/patent/US10953712B2/en)
