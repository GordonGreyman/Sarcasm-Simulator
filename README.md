# Sarcasm-Simulator
Recursive Pragmatic and Game Theoretic Inference Simulation

How to Open The File:

1. Download the files
2. Extract the files from the zip
3. Double click to open the html file

How to Use the Simulator:

1. Definitions:
1.1. Literal Meaning (T): A variable that indicates whether the uttered sentence is literal (0) or sarcastic (1).

1.2. Contextual Cue (C): A variable that represents the situational context, affecting the interpretation of the utterance (0 = Neutral, 1 = Sarcastic).

1.3. Speaker Strategy (S): A variable that reflects the speaker’s intent, demonstrating how they wish their message to be perceived (0 = Neutral, 1 = Sarcastic).

1.4. Listener Inference (L): A variable that shows how the listener interprets the utterance based on their understanding and context (0 = Neutral, 1 = Sarcastic).

2. Adjustment:
To interact with the simulator, adjust the variables using the sliders provided:

2.1. Pull the slider to set the value for Literal Meaning (T), Contextual Cue (C), Speaker Strategy (S), and Listener Inference (L) according to your preference (values range from 0 to 1).

2.2. Set the Number of Iterations: Adjust the number of iterations (recursion steps) by pulling the corresponding slider. This determines how many times the simulation updates the interpretation based on the defined parameters.

2.3. Enable Game Theory Adjustment: To incorporate a game-theoretic perspective into the simulation:

Check the box labeled “Enable Speaker Payoff and Listener Risk Aversion (Game–Theoretic Adjustment).” This will add an additional layer to the simulation, affecting the final interpretations based on strategic choices.

3. Running the Simulation:
Once you have set all the parameters:

3.1. Click the “Run Simulation” button. This will execute the simulation based on your chosen values, iteratively adjusting the intended meaning.

3.2. View Output: The output section will display:

The history of iterations (Δ values).
The final intended meaning (I*).
The raw difference from the literal meaning.
The normalized interpretation (a score between 0 and 1 indicating sarcasm level).
4. Interpretation of Results:
After running the simulation, review the output:

4.1. Interpretation: The simulator will provide a clear statement of whether the utterance is interpreted as literal or sarcastic based on the normalized score:

0 = Literal
1 = Sarcastic


