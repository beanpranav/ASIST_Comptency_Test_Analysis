# ASIST_competency_analysis
Notebook for analyzing Minecraft competency data and creating a skill index for participants

### Directions for use:
- Save and Open .ipynb  
- Place the 'functions.py' in the same directory
- Place the 'competency_data_analysis.csv' in the same directory
- Update the path to your Data Folder in the .ipynb (first cell)
- Run cells
- Generates intermediary dataframe for time taken for each task in the competency test
- Calculates skill index and exports in 'competency_skill_estimates.csv' in the current directory.
- Note: interpretation discussed in the notebook and below.

### Interpretation of Skill Estimates
- Each cell indicates the a skill index in terms of time impact on performance for each instance of skill is used during a task.
- Example 1: walk = 0.36 means this player requires addition 0.36s for each step they need to take.
- Example 2: obstacle = -0.39 means this player saves 0.39s for each obstacle they jump over (may indicate they are better at jumping over 3-4 blocks as against walking 3-4 blocks)
- Note rescue skills are static by tasks design. In the future this may be varied across participants.
