# Western-Eng-Competition
🌊 **Abyss Explorer**

A simple deep-sea exploration game created for the Western Engineering Competition (WEC).
The player controls a submarine on a 10×10 grid (each cell = 1 km²).
Your goal is to complete missions, survive hazards, and learn about the deep sea with help from an onboard AI assistant.

**Features**

- 10×10 world grid including depth, temperature, pressure, wildlife, hazards, and currents

- Timed missions (e.g., locate a vent, find a biodiversity zone, scan a trench)

- AI assistant that provides:
  - mission briefings
  - success and failure messages
  - hints
  - warnings for hazards and predators

- Basic survival elements such as pressure effects, temperature changes, and environmental dangers

**How It Works**

- The world is loaded into a 2D grid based on the dataset

- The AI assistant uses a message queue so messages appear one at a time without overlapping

- Each turn, the game checks:
  - player movement
  - environment effects
  - mission progress
  - warnings and hints from the assistant

**Team**

Created for the Western Engineering Competition (WEC) Programming Division, 2025.
Team: Patricia Ashley Kamde, Jordan Carvalho, Brandon Chyn, Owen Sinclair
 
  
