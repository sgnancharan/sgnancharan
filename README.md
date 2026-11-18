<a name="charan-profile">
  <picture>
    <source media="(max-width: 600px)" srcset="./assets/compute-mobile.svg">
    <img src="./assets/compute.svg" width="100%" alt="S. Gnan Charan — local AI, Linux and software. An animated compute die on a circuit board.">
  </picture>
</a>

I'm Charan, an AI & ML student at NIAT / NSRIT in Vizag. I run local models, keep a Debian homelab, and like a bug I can reproduce.

[Meet ARYA](#building-arya) · [Explore the projects](#selected-projects) · **[Play the README arcade ↓](#readme-arcade)**

## Building ARYA

**“Hey Arya” or just “Arya.”** My PC listens for both wake phrases so I can call it hands-free, anytime. Behind them is a **27B Qwen 3 model running locally on my RTX 5060 Ti PC**. I wanted my everyday assistant to have a name of its own.

I’m setting up **Home Assistant** to connect ARYA to the appliances around my home. The goal is to control both my PC and the house in one conversation. The command I’m building toward is *“Arya, turn on my desk light and open my project.”*

<details>
<summary>Inside ARYA · how I want that command to work</summary>

<a name="arya-wake-display"><img src="./assets/arya.svg" width="600" alt="Illustrated wake signals for “Hey Arya” and “Arya”."></a>

| Part of the request | Intended destination |
| --- | --- |
| “Turn on my desk light” | Home Assistant routes the action to the paired light. |
| “Open my project” | The PC opens my workspace so it is ready when I sit down. |

</details>

## Selected projects

### MediGuide AI

Two formulations can share a medicine name. My college hackathon prototype asks you to choose the matching record before a local MedGemma model explains it. Telugu is one of **eight language options**. The **79-test suite** covers ambiguous names, language selection and what happens when the model goes offline.

[Source and setup](https://github.com/sgnancharan/Ai-Agent-For-Drug-Indentification) · [Read the integration tests](https://github.com/sgnancharan/Ai-Agent-For-Drug-Indentification/blob/main/tests/end-to-end-integration.test.ts)

### Ganesh: The Quest

Our team built a 2.5D festival game where you assemble a pandal, cook modaks and play dhol in the procession. I worked on the backgrounds with Nikhil, fixed photo mode so it captures the whole scene, and corrected the lighting for the final immersion.

[Festival game demo ↗](https://ganesh-the-quest-game.vercel.app/) · [Source](https://github.com/sgnancharan/ganesh-the-quest) · [My camera and lighting fixes](https://github.com/sgnancharan/ganesh-the-quest/commit/3b5016e370dc5f05d04c16974e407ce48e9fa1f2)

### Little Listen Lab

Give the app a topic and it sends it to a podcast-generation workflow, checks the audio URL it gets back, and plays the episode in the browser. I added a webhook switcher so I can keep using the app when the tunnel address changes. It remembers the new endpoint on my next visit.

[Source and setup](https://github.com/sgnancharan/little-listen-lab) · [Follow a podcast request](https://github.com/sgnancharan/little-listen-lab/blob/main/src/lib/podcast.functions.ts)

<details>
<summary><strong>Four more builds · film, hardware, fiction and games</strong></summary>

| Project | What you can do with it |
| --- | --- |
| [MovieStream](https://github.com/sgnancharan/moviestream) | Pick a movie or series by genre and language, see its streaming providers, and keep your watch history for the next movie night. |
| [Onyx Studio Lab](https://github.com/sgnancharan/onyx-studio-lab) | Explore local tech services, from custom PC assembly to home networking. A built-in estimator lets you price out the work. |
| [ORV Character Generator](https://github.com/sgnancharan/orv-character-generator) | Turn your name and photo into an *Omniscient Reader’s Viewpoint* character, draw a sponsor, and save the illustrated card as a PNG. |
| [Jaldi 5](https://github.com/sgnancharan/jaldi-5) | Track tickets, prizes and change owed. When a player wins, the app calculates the cash to hand over and records the payout. |

</details>

## README arcade

Open a game below. Clear **one bank, trace or capture per game** to collect its two-digit hex byte. The three bytes unlock the console at the bottom.

<details>
<summary><strong>Play Echo Array · memory</strong></summary>

Watch the four pads from **SYNC**. Remember which letters light up, then select them one at a time.

<details>
<summary>Bank A · 3 keys</summary>

<details>
<summary>Watch the signal</summary>

<a name="echo-feed-a"><img src="./assets/echo-a.svg" width="550" alt="Animated sequence for bank A. Start at SYNC, or open the text feed."></a>

<details>
<summary>Read the text feed</summary>

The keys arrive as **K → H → J**.

</details>

</details>

Close the signal when you have it. Enter the first key.

<details>
<summary><code>H</code></summary>

Key 1 missed. Close this choice and try another key.

</details>

<details>
<summary><code>J</code></summary>

Key 1 missed. Close this choice and try another key.

</details>

<details>
<summary><code>K</code></summary>

Key 1 matched. Enter key 2.

<details>
<summary><code>H</code></summary>

Key 2 matched. Enter key 3.

<details>
<summary><code>H</code></summary>

Key 3 missed. Close this choice and try another key.

</details>

<details>
<summary><code>J</code></summary>

**Cache hit. Every key matched.** Your console byte is **`56`**.

</details>

<details>
<summary><code>K</code></summary>

Key 3 missed. Close this choice and try another key.

</details>

<details>
<summary><code>L</code></summary>

Key 3 missed. Close this choice and try another key.

</details>

</details>

<details>
<summary><code>J</code></summary>

Key 2 missed. Close this choice and try another key.

</details>

<details>
<summary><code>K</code></summary>

Key 2 missed. Close this choice and try another key.

</details>

<details>
<summary><code>L</code></summary>

Key 2 missed. Close this choice and try another key.

</details>

</details>

<details>
<summary><code>L</code></summary>

Key 1 missed. Close this choice and try another key.

</details>

</details>

<details>
<summary>Bank B · 4 keys</summary>

<details>
<summary>Watch the signal</summary>

<a name="echo-feed-b"><img src="./assets/echo-b.svg" width="550" alt="Animated sequence for bank B. Start at SYNC, or open the text feed."></a>

<details>
<summary>Read the text feed</summary>

The keys arrive as **L → J → J → H**.

</details>

</details>

Close the signal when you have it. Enter the first key.

<details>
<summary><code>H</code></summary>

Key 1 missed. Close this choice and try another key.

</details>

<details>
<summary><code>J</code></summary>

Key 1 missed. Close this choice and try another key.

</details>

<details>
<summary><code>K</code></summary>

Key 1 missed. Close this choice and try another key.

</details>

<details>
<summary><code>L</code></summary>

Key 1 matched. Enter key 2.

<details>
<summary><code>H</code></summary>

Key 2 missed. Close this choice and try another key.

</details>

<details>
<summary><code>J</code></summary>

Key 2 matched. Enter key 3.

<details>
<summary><code>H</code></summary>

Key 3 missed. Close this choice and try another key.

</details>

<details>
<summary><code>J</code></summary>

Key 3 matched. Enter key 4.

<details>
<summary><code>H</code></summary>

**Cache hit. Every key matched.** Your console byte is **`56`**.

</details>

<details>
<summary><code>J</code></summary>

Key 4 missed. Close this choice and try another key.

</details>

<details>
<summary><code>K</code></summary>

Key 4 missed. Close this choice and try another key.

</details>

<details>
<summary><code>L</code></summary>

Key 4 missed. Close this choice and try another key.

</details>

</details>

<details>
<summary><code>K</code></summary>

Key 3 missed. Close this choice and try another key.

</details>

<details>
<summary><code>L</code></summary>

Key 3 missed. Close this choice and try another key.

</details>

</details>

<details>
<summary><code>K</code></summary>

Key 2 missed. Close this choice and try another key.

</details>

<details>
<summary><code>L</code></summary>

Key 2 missed. Close this choice and try another key.

</details>

</details>

</details>

</details>

<details>
<summary><strong>Play Clock Edge · timing</strong></summary>

The cursor sweeps across a six-tick bus. Read the register at the instant the cursor crosses **LATCH**, then select that value. Each sweep repeats.

<details>
<summary>Trace A · normal speed</summary>

<a name="clock-trace-a"><img src="./assets/clock-a.svg" width="550" alt="Clock trace A. Read the register at the dashed latch. A text trace follows."></a>

<details>
<summary>Step through the text trace</summary>

The latch is at tick **4**.

| Tick | 1 | 2 | 3 | 4 | 5 | 6 |
| --- | --- | --- | --- | --- | --- | --- |
| Register | `2D` | `74` | `B1` | `9C` | `4E` | `A7` |

</details>

Which value was on the bus at the latch?

<details>
<summary><code>0x4E</code></summary>

You sampled tick 5, after the latch. Watch the cursor cross the dashed line and try again.

</details>

<details>
<summary><code>0x9C</code></summary>

**Clock locked. Register `9C` was on the bus at tick 4.** Your console byte is **`49`**.

</details>

<details>
<summary><code>0xB1</code></summary>

You sampled tick 3, before the latch. Watch the cursor cross the dashed line and try again.

</details>

</details>

<details>
<summary>Trace B · fast scan</summary>

<a name="clock-trace-b"><img src="./assets/clock-b.svg" width="550" alt="Clock trace B. Read the register at the dashed latch. A text trace follows."></a>

<details>
<summary>Step through the text trace</summary>

The latch is at tick **2**.

| Tick | 1 | 2 | 3 | 4 | 5 | 6 |
| --- | --- | --- | --- | --- | --- | --- |
| Register | `03` | `C8` | `62` | `D1` | `57` | `E4` |

</details>

Which value was on the bus at the latch?

<details>
<summary><code>0x03</code></summary>

You sampled tick 1, before the latch. Watch the cursor cross the dashed line and try again.

</details>

<details>
<summary><code>0x62</code></summary>

You sampled tick 3, after the latch. Watch the cursor cross the dashed line and try again.

</details>

<details>
<summary><code>0xC8</code></summary>

**Clock locked. Register `C8` was on the bus at tick 2.** Your console byte is **`49`**.

</details>

</details>

</details>

<details>
<summary><strong>Play Parity Patch · debugging</strong></summary>

One bit flipped in transit. Each original byte had an **even** number of ones, and XOR of any two originals gives the third. Find the bad frame, then recover its value.

<details>
<summary>Capture A</summary>

Pick the frame with the flipped bit.

<details>
<summary><code>A　1010 0101</code></summary>

This byte has 4 ones. Its parity is even. Check a different frame.

</details>

<details>
<summary><code>B　0011 1101</code></summary>

Odd parity. To reconstruct frame B, XOR the two good bytes. Which value should replace it?

<details>
<summary><code>0x38</code></summary>

That byte fails the cross-check. XOR sets a bit wherever the two good bytes differ.

</details>

<details>
<summary><code>0x3C</code></summary>

**Frame repaired. XOR returns `0x3C`.** Your console byte is **`5A`**.

</details>

<details>
<summary><code>0x3D</code></summary>

That byte fails the cross-check. XOR sets a bit wherever the two good bytes differ.

</details>

</details>

<details>
<summary><code>C　1001 1001</code></summary>

This byte has 4 ones. Its parity is even. Check a different frame.

</details>

</details>

<details>
<summary>Capture B</summary>

Pick the frame with the flipped bit.

<details>
<summary><code>A　0110 0110</code></summary>

This byte has 4 ones. Its parity is even. Check a different frame.

</details>

<details>
<summary><code>B　0101 0101</code></summary>

This byte has 4 ones. Its parity is even. Check a different frame.

</details>

<details>
<summary><code>C　0010 0011</code></summary>

Odd parity. To reconstruct frame C, XOR the two good bytes. Which value should replace it?

<details>
<summary><code>0x32</code></summary>

That byte fails the cross-check. XOR sets a bit wherever the two good bytes differ.

</details>

<details>
<summary><code>0x33</code></summary>

**Frame repaired. XOR returns `0x33`.** Your console byte is **`5A`**.

</details>

<details>
<summary><code>0x37</code></summary>

That byte fails the cross-check. XOR sets a bit wherever the two good bytes differ.

</details>

</details>

</details>

</details>

<details>
<summary><strong>Unlock the console · 3 bytes</strong></summary>

Choose the bytes you collected, in the order the games appear above.

<details>
<summary><code>49 56 5A</code></summary>

The order is off. Read the bytes from Echo Array, Clock Edge, then Parity Patch.

</details>

<details>
<summary><code>56 5A 49</code></summary>

The order is off. Read the bytes from Echo Array, Clock Edge, then Parity Patch.

</details>

<details>
<summary><code>56 49 5A</code></summary>

<a name="vizag-console-display"><img src="./assets/vizag.svg" width="540" alt="Console unlocked. Hello, Vizag!"></a>

**Console unlocked.** Your bytes spell `VIZ` in ASCII. Hello from Visakhapatnam. — Charan

</details>

</details>

## Homelab and teamwork

I run Jellyfin on Debian and use the same homelab for Docker Swarm and boot-recovery experiments. I was technical lead on our six-person Vertithron team, handling architecture, API integrations and debugging.

[All repositories](https://github.com/sgnancharan?tab=repositories) · [LinkedIn](https://www.linkedin.com/in/s-gnan-charan-994a1b349/) · [Email me](mailto:sgnancharan730@gmail.com)
