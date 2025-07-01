# Typo Report for Prismatic Adventure

I've reviewed the files in the Prismatic Adventure folder and found the following obvious typos that need correction:

## 1. zones.js

### Line 155: "Deplot" should be "Deploy"
- **File**: `prismatic_adventure/zones.js`
- **Line**: 155 (task id 112)
- **Current**: `{ id: 112, name: "Deplot Cyber Barrier", type: "Training", maxReps: 2, count: 0, baseTime: 3e10, xpMult: 1.2, description: "Deploy a robust digital defense.", skills: ["hacking", "quantum"], mandatory: true },`
- **Issue**: Task name says "Deplot" but should be "Deploy" (as correctly used in the description)
- **Fix**: Change `"Deplot Cyber Barrier"` to `"Deploy Cyber Barrier"`

### Line 189: "Synethesize" should be "Synthesize"
- **File**: `prismatic_adventure/zones.js`  
- **Line**: 189 (task id 135)
- **Current**: `{ id: 135, name: "Produce Augment Fuel", type: "Training", maxReps: 4, count: 0, baseTime: 1e18, xpMult: 0.5,description: "Synethesize some augment fuel.", skills: ["cybernetics", "mechanics"], resources: ["augment_fuel"] },`
- **Issue**: Description says "Synethesize" but should be "Synthesize"
- **Fix**: Change `"Synethesize some augment fuel."` to `"Synthesize some augment fuel."`

### Line 408: "Dimesion" should be "Dimension"
- **File**: `prismatic_adventure/zones.js`
- **Line**: 408 (task id 286)  
- **Current**: `{ id: 286, name: "Dimesion Mastery: Grasp Multiverse", type: "Training", maxReps: 3, count: 0, baseTime: 1e15, speedMult: 1e-8, drainMult: 1e3, xpMult: 1e-3, description: "Attune yourself to the symphony of infinite realities.", skills: ["intellect", "totality"], perk: "dimension_mastery" },`
- **Issue**: Task name says "Dimesion" but should be "Dimension" (perk name is correctly spelled as "dimension_mastery")
- **Fix**: Change `"Dimesion Mastery: Grasp Multiverse"` to `"Dimension Mastery: Grasp Multiverse"`

## Summary

Found **3 typos** total:
1. "Deplot" → "Deploy" 
2. "Synethesize" → "Synthesize"
3. "Dimesion" → "Dimension"

All typos are in the `zones.js` file in task names or descriptions. The rest of the files I checked (including `index.html`, `tutorial.js`, `game.js`, and `resources.js`) appear to be free of obvious spelling errors.

## Note

I performed comprehensive searches for common typos across the JavaScript files and these were the only obvious spelling mistakes found. The code appears to be generally well-written with good spelling throughout.