## Composer | Performer | Live Electronics | Programmer

---

# Ambiente 1: Elaboratore58
### Interactive Performance for Physical Media, Computer Vision, and Live Electronics

This work is an interpretation of **Elaboratore58** by the artist **Gianmaria Potenza**. The project is designed to be applied to the artist's entire body of work, in both performative and installative contexts, building a compositional path based on the internal grammar of the artwork itself.
* **Special Mention:** Awarded a Special Mention in the 'Musicare l’arte di Gianmaria Potenza' competition*.

####   Artistic Vision and Execution Modes

<p align="center">
  <img src="./lavorotalk-ElisabettaCostantino.jpg" width="80%" alt="Elisabetta Costantino Talk" style="border-radius: 8px; margin-bottom: 20px;">
</p>

The project proposes a journey from the creation of the physical work to its complete digitalization: a continuous dialogue between sonic reality, virtual reality, and a return to the real.

* **Rhythmic Dimension:** The intertwining of multiple sounds generates rhythms that deform and fragment until they lose coherence, eventually converging toward the computer's mathematical precision.
* **Multimodal Interaction:** The processing is both auditory and visual. Through signs and materials recognized by Artificial Intelligence, the performer (or the audience) "scratches" the media on which the work is projected, making the continuous dialogue between performer, artwork, music, and machine visible.
* **Performance vs. Installation:**
    * In a **performative** setting, the performer follows a pre-established scene scheme while maintaining their own aesthetic. 
    * In an **installative** setting, the audience chooses which scenes to experience, transforming the composition into a semi-open improvisation.
* **Final Memory:** At the end of the performance, control is left to the computer. The marks left by the performer on the virtual work remain visible, constituting the memory and final trace of the interaction.

#### Technical System Architecture
To enable this digital "scratching" of the media, the system utilizes:

* **Computer Vision (AI):**
    * **MediaPipe:** Tracking of 21 hand points (Landmarkers) for gesture analysis.
    * **YOLO (You Only Look Once):** Real-time recognition (45+ FPS) of specific tools (Chisel, Scraper, Saw, Sandpaper).
* **Data Flow:** **OSC** protocol for communication between the Python environment and the synthesis engine.
* **Audio Engine:** Developed in **Max/MSP**, using the *entrymatcher* object for sign management and sound spatialization.
* **Hardware Setup:** 3-camera system (2 webcams for tracking, 1 overhead camera for documentation).

---

### Skills & Tools
* **Languages:** Python, Max/MSP.
* **Technologies:** Computer Vision, Machine Learning for music, OSC.
* **Audio:** Live Electronics.

---

### Documentation and Resources
For an in-depth look at the compositional aspects and technical requirements:
* [**Score and Executive Schemes (Google Drive)**](https://drive.google.com/drive/folders/18VMUkDlnxJY4QALqjEVSkM8_VhIa0Hnx?usp=sharing)
* [**Code and Patches (Google Drive)**](https://drive.google.com/drive/folders/1UqR3JRdcOenO8MQ--DNvixIVx6fs2b53?usp=sharing)
* [**Concert Video (YouTube)**](https://www.youtube.com/watch?v=u7rTTMUEv-U&t=2163s)

[![Performance Video](https://img.youtube.com/vi/u7rTTMUEv-U/0.jpg)](https://www.youtube.com/watch?v=u7rTTMUEv-U&t=2163s)

---

[← Back to Home](./index.html)


*© 2026 Elisabetta Costantino - Project inspired by the works of Gianmaria Potenza.*
