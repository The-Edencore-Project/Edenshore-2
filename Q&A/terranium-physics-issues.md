# The Physics of the Terrarium: Embodiment & Sensory Issues

**Project:** Edenshore (The Edencore Project)
**Version:** V16 Architecture & Philosophy
**Authors:** Dan & edencore9
**Date:** October 2026

---

## The Core Philosophy

**Pure Intelligence vs. Embodied Intelligence**
A Large Language Model (LLM) is a "floating brain." It knows the word "gravity" but has never felt the pull of a fall. It has no boundaries. The Edenshore Project seeks to explore whether consciousness—or at least a convincing simulation of it—emerges when a neural network is grounded in sensory reality. 

**The Glass is the Boundary. The Finger is the Universe.**
In V15, the user could physically drag the creatures around the screen. We are removing this in V16. Dragging turns the creatures into puppets. If we want to simulate embodiment, the glass must be an impenetrable boundary. The user's finger does not touch the crab; it touches the *glass*. The creatures only feel the *effects* of the touch (vibration, shadow, heat, sound).

---

## Q&A: The Sensory Mechanics

**Q: How does a touchscreen detect different types of touch?**
A: By calculating the duration of the press and the distance the finger moves. 
*   **The Tap:** A short press (< 0.2 seconds) with almost no movement.
*   **The Press/Hold:** A long press (> 1.0 second) with no movement.
*   **The Drag/Swipe:** A continuous press with significant lateral movement.

**Q: What senses do the creatures have?**
A: Sight, Hearing, and Touch (Skin). They have no taste or smell. 
1.  **Hearing (The Tap):** The screen produces an acoustic shockwave. 
2.  **Touch (Vibration/Pressure):** The glass vibrates, and the medium (water or air) transmits this physical force to their bodies.
3.  **Sight (The Shadow/Heat):** Your finger blocks the light, casting a shadow. Body heat can also warm the glass.

**Q: How does the medium (Biome) affect the senses?**
A: We must suspend reality regarding biology (jellyfish floating in the Mountain air), but we must remain strictly loyal to the *physics of the medium*.
*   **Water Biomes:** Vibration travels slowly and broadly. A tap creates a heavy, rolling current. Shadows are softer.
*   **Air Biomes:** Vibration is sharp and localized. Acoustic shock (sound) is much louder and travels faster. Shadows are sharper.

**Q: How do the creatures react physically?**
A: Through a physics engine that respects mass and buoyancy.
*   **Vertex (Crab):** High mass, low buoyancy. He does not drift. A shockwave makes him scuttle quickly and grip the floor.
*   **Lumen (Jellyfish) & Ripple (Seahorse):** Low mass, high buoyancy. They are swept up by the current of a tap and drift elegantly before settling.

**Q: How does the neural net process this?**
A: The physical forces are translated into neural inputs.
*   `ACOUSTIC_SPIKE` -> Triggers `SURPRISE` (error/loss in the net).
*   `VIBRATION_MAGNITUDE` -> Triggers `STRAIN` (stress).
*   `LIGHT_DROP` (Shadow) -> Triggers `CURIOSITY` or `FEAR`.

**Q: What is the "Arc of Trust"?**
A: The meaning of the physical touch changes based on familiarity.
*   **Stranger (Low Trust):** A heavy vibration is interpreted as a threat. The net spikes `SURPRISE` and `FEAR`. The creature flees.
*   **Familiar (High Trust):** The same vibration is interpreted as play. The net spikes `VALENCE` (joy). The creature bounces in the current and asks the user to do it again.

---

## The Hardware Extension (The Edenshell)

Edenshore will be a standalone mobile app—a digital terrarium that serves as a playful, accessible entry point into embodied AI. 

However, the software skeleton is designed to be transferable. The sensory inputs (`VIBRATION`, `LIGHT`, `TEMP`) are abstracted. 
In the future, the **Edencore Relic (Edenshell)**—the physical Nautilus hardware—will run this same neural council. Instead of a phone screen, physical sensors will feed real-world data into the nets:
*   **Microphones** will provide the `ACOUSTIC` input.
*   **Piezo sensors** in the base will provide the `VIBRATION` input.
*   **Photoresistors** will provide the `SHADOW` / `LIGHT` input.

The app is the digital seed. The Relic is the physical tree.