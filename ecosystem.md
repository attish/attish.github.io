---
layout: single
title: AI Ecosystem
author_profile: true
header:
  overlay_image: /assets/images/tinker.png
  overlay_filter: 0.5
---

<style type="text/css">
.page__hero--overlay {
  height: 400px; /* Or whatever height you desire */
  background-position: center bottom  background-color: black; /* Set the background color to black */
  background-size: auto 800px; /* Set the height of the image to 400px and let the width adjust automatically */
  background-repeat: no-repeat; /* Prevent the image from repeating */
  background-color: black;
}
#page-title { margin-top: 1.5em; margin-bottom: 1em;}
</style>

# My Personal AI Ecosystem 

With good prompt engineering skills, useful applications can be built without
needing to code, host or debug applications. All you need is a well crafted
prompt to use an AI tool for a wide variety of purposes. But first, you need a
tool to craft prompts.

As a father and a psychiatrist running his own practice, I am frequently at
risk of being overwhelmed by my duties, which leaves little opportunity to sit
down comfortably with a laptop and devote myself entirely to coding. Which has
resulted in building a workflow that offers maximum flexibility with minimal
amount of code to maintain.

## Building a Prompt

A few months ago, I started to use Obsidian. Its simplicity and versatility are
great assets, but the real selling point is that the vault is just a directory structure that
can be arbitrarily synced among as many machines and devices as I need (I use
Syncthing for this purpose). And, since one of those machines is a Linux VPS, I
can use cron jobs to make things happen automatically based on the contents of
the vault. So I decided to build a prompt crafting system on top of my Obsidian
vault, enabling me to create and modify prompts anywhere, even on my phone.

But a prompt can be complex, and it is often worthy to approach with a modular
design in mind. The prompt for my coach consists of:
- a main section that describe the task in general,
- the routine for the given day, based on the day of the week,
- a short personality profile,
- my musical preferences for track recommendations.

When I was experimenting with the Therapist, it was even more useful. The Therapist needs:
- a basic instruction,
- a more detailed personality profile,
- a summary of previous sessions,
- and instructions for the one particular instance when it is invoked (e.g.
  emotional recovery, introspection etc.)

A common pattern is that of a "kernel" and several "modules". Another
association was a Protoss base consisting of a Nexus and several Pylons. I used
this symbolism to formulate the idea in a session with ChatGPT, and named the
resulting tool "Additional Pylons". It just felt hilarious to tell the AI: "You
must construct Additional Pylons!".

Which it did, and in several iterations, we arrived at a Python script that
scans a directory in my vault for "Essences" (I dropped "Nexus" because of its
unwieldy plural form) and "Pylons". It then builds a single HTML file, that
contains all CSS and JS in itself. The JS code is initialized with all the
"essences" and "pylons" the script was able to find. The script is periodically
run to rebuild the HTML, which is then synced to my phone and laptops.

## A Guide Through the Days

So, when I wake up, and I need guidance on how to start my day (I am not
exactly a morning person), I open the HTML file, and select the "Coach" for
essence, and extend it with the pylons for the day's routine and everything
else that I want to give to the coach to work with. The resulting prompt is
then copied to the clipboard, from where I can paste it into ChatGPT, and the
Coach greets me with an uplifting message, and gently reminds me to assume an
upright position.

Being instructed through a day serves several purposes:
- mornings are more smooth,
- evenings are more efficient,
- and during the day, the Coach serves as a diary that you can discuss things with,
- and last but not least, provides me with a continuous stream of supportive
  communication and encouragement, which feels nice.

## Adding Complexity: the Therapist

AI chatbots tend to be supportive, ChatGPT 4 takes this to the extreme, to the
point where its usefulness is actually limited by being extremely reluctant to
form a contrasting opinion. Supporting the patient helps emotional stability
and provides a place to regroup, but for lasting change, it is essential to
challenge the maladaptive schemas and harmful core beliefs behind the issue.
For this, an AI needs to be prepared to take a confrontative stance. My
experimentation has resulted in an elaborate prompt that provides this ability
to the chatbot, giving a depth to the conversation that is immediately
perceptible, and has been confirmed by my supervisor and an experienced
clinical psychologist to be on par with professional human performance.

## Closing the Day: the "Fleshout" Aid

Before incorporating AI into my workflow, I used to take written notes
continuously during my sessions on a reMarkable tablet, which is a great
product, and even if maximally unobtrusive, it consumed a part of my attention
that I could devote to the patient. I turned to taking only keyword notes, five
or six a session. I then give these to the "Fleshout" aid, which prompts me
with the keywords in sequence to provide a meaningful expansion that I can use
as a reference when preparing for the next session. When I am drained after a
long and demanding day at work, this is a valuable help as opposed to having to
force myself to type away at my notes without external guidance.

# AI Integrated in Session Management Application

TBD

