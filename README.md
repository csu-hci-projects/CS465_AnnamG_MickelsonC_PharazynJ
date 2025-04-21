# CS456 Checkpoint 2 – Fitts’ Law in VR Interaction

## Project Overview

This project explores how object size and distance affect interaction time in virtual reality using Fitts’ Law. The goal is to identify the most efficient object parameters (size and placement) for 3D selection, movement, and disengagement tasks in VR.

We are building a VR experience in Unreal Engine where a user must pick up color-coded objects from a virtual table and place them in the correct bins. All interactions are tracked and logged to CSV for later analysis.

## Current Progress

- ✓ Unreal Blueprint logic implemented for object grabbing, bin detection, and timing (T1/T2)  
- ✓ Basic test scene built with randomized object generation  
- ✓ CSV logging system recording S, D, T1, T2 for each interaction  
- ✓ User instructions and input flow established  
- ○ Prototype not fully polished yet (missing final polish and UX adjustments)  
- ✗ Subjects have not been run yet  
- ○ LaTeX paper is in progress  
- ○ Progress and code discussion videos are being recorded


## Team Contributions

- **Calvin Mickelson**  
  - Wrote updated project proposal  
  - Built Unreal Engine blueprint prototype  
  - Implemented CSV export and time tracking  
  - Began work on LaTeX formatting and created demo video

- **Jakob [Last Name]**  
    - walked me through a lot.
    - Will set up randomized object sizing and distance logic  

## Data Collection Plan

Each trial logs the following:
- `S`: Object size (grab width in cm)
- `D`: Distance from hand to bin in 3D space
- `T1`: Time to initiate grab
- `T2`: Time to complete placement

### Participants

- 10 subjects x 10 trials = 50 object interactions per person
- Sessions last approximately 20 minutes per participant

### Data Analysis

- Use Fitts’ Law to calculate interaction efficiency
- Run ANOVA to compare size and distance variables
- Determine optimal object sizing and placement based on collected timing data

## Deliverables

### Video Links

- [Progress Video (Prototype Demo)](LINK_GOES_HERE)
- [Code Walkthrough](LINK_GOES_HERE)

### GitHub Repo Contents

- `Source/` – Unreal Engine project
- `Paper/` – LaTeX document using CHI template (in progress)
- `README.md` – This file
- `References.bib` – (In progress)
- `Output/` – CSV log files

### Paper (PDF)

- [Download Paper (CHI LaTeX Template)](LINK_TO_PDF)

## To Be Completed

- Finalize full VR prototype polish
- Record final required videos
- Collect data from test subjects
- Finish writing and formatting full LaTeX paper
- Add references (target: 10+ scholarly sources)