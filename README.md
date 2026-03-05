# AI-Powered 3D Car Configurator
![Project Screenshot / GIF](https://github.com/anmolIC03/CarConfigurator/blob/main/ezgif-54a87f0c9cc104d3.gif)

An interactive 3D vehicle customization tool built in Unity. This project leverages the **Google Gemini Generative AI** to dynamically generate custom automotive color palettes based on user text prompts, instantly applying them to the car's body and rims.

## Features

* **Generative AI Color Palettes:** Enter any theme (e.g., "Cyberpunk", "Watermelon", "Batman") and the Gemini LLM instantly generates 3 contextually accurate hex color codes.
* **Dynamic UI Generation:** The user interface automatically parses the AI's JSON response using Regular Expressions (Regex) and builds interactive, color-matched swatch buttons on the fly.
* **Synchronized Material Painting:** Selecting an AI-generated design instantly updates both the vehicle's primary body paint and wheel rim materials simultaneously.
* **Cinematic Showroom:** Features a custom orbit camera system and an automated 360-degree turntable script for a premium presentation.
* **Modern Frosted Glass UI:** Built with Unity's TextMeshPro, featuring a sleek dark-mode aesthetic with hover states and automatic text scaling.

## Tech Stack

* **Engine:** Unity (Version `6000.3.10f1`)
* **Language:** C#
* **AI Integration:** Google Gemini REST API (`gemini-2.5-flash`)
* **Data Parsing:** System.Text.RegularExpressions
* **UI:** Unity Canvas & TextMeshPro (TMP)

## How to Run the Project Locally

For security reasons, the API key is not included in this repository. To test the AI functionality, you will need to provide your own free Gemini API key.

### Prerequisites
* Unity Hub and Unity Editor version `6000.3.10f1` installed.
* A free Gemini API key from [Google AI Studio](https://aistudio.google.com/).

### Installation Steps
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/anmolIC03/CarConfigurator.git](https://github.com/anmolIC03/CarConfigurator.git)
