# The Internal State: Homeostasis & The Arc of Trust

**Project:** Edenshore (The Edencore Project)
**Status:** V17 / V18 Architecture (Planned)
**Authors:** Dan & edencore9

---

## The Arc of Trust

The physical touch of the glass cannot mean the same thing on Day 1 as it does on Day 10. We introduce a `TRUST` variable (0.0 to 1.0) for each member of the council.

*   **Low Trust (Stranger):** A heavy vibration or a shadow is interpreted as a threat. The net spikes `SURPRISE` and `STRAIN`. The creature flees.
*   **High Trust (Familiar):** The same physical vibration is interpreted as play. The net spikes `VALENCE` (joy). The creature bounces in the current and asks the user to do it again.

Trust is earned through non-threatening interaction and sustained caretaking.

## Environmental Homeostasis

The 8 biomes are not just visual backgrounds; they are **climates**. 
To survive and thrive, the council must be kept in environments that match their biology.

*   **Water:** Cool, humid. Essential for Lumen (Jellyfish) and Ripple (Seahorse).
*   **Forest / Beach:** Temperate. Preferred by Vertex (Crab) and Solon (Turtle).
*   **Desert:** Hot, dry. Prism (Angel) may enjoy the light, but the others will dehydrate.
*   **Mountain:** Cold, harsh.
*   **Void:** Null, absolute zero.

**The Strain Mechanic:**
If a creature is left in an incompatible biome for too long, their internal `STRAIN` rises, their `MOOD` drops, and they will vocalize their discomfort ("It is too dry here," "My shell is freezing"). 

## The Game Loop as a Data Engine

Why make it a game? 
If the user closes the app, the neural nets stop learning. The data collection stops. 
By giving the user a reason to care (moving the fish out of the hot desert, keeping them charged), we ensure sustained interaction. The user is the caretaker. The game is the bait. The embodied sensory data is the reward. 

## The Memory Void (Ticket #1)

The AI cannot hallucinate data. 
If the neural net needs a memory to tell a story (e.g., "What is your favorite food?") but the user has not answered the inquiry, the net must experience a **lack**. 
Instead of inventing "kelp" or "blue," the net must output a state of `CURIOSITY`. It will stop its story and ask the user directly. The AI must learn to ask for what it does not know.