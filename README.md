\# Mounjaro® Dosing Steady-State Calculator



This is an educational web-based tool to visualize how different dosing schedules of Mounjaro® (Tirzepatide) can affect the total amount of the drug in the system over time. It uses a simplified pharmacokinetic model based on the drug's known half-life to chart the accumulation and elimination of the drug, helping users understand the concept of a steady state.



The calculator is built with HTML, JavaScript, and Tailwind CSS, with Chart.js for data visualization.



\## Important Medical Disclaimer



This tool is for \*\*educational and informational purposes ONLY\*\*. It is a simplified model and does not represent real physiological processes. The results are not medical advice. \*\*ALWAYS consult with a qualified healthcare professional\*\* before making any decisions about your medication or treatment plan. Do not use this tool to self-medicate or adjust your dosage.



\## How to Use



Simply open the `index.html` file in a web browser. You can adjust the following parameters to see the simulation update in real-time:



\* \*\*Dose Amount:\*\* Use the slider to set the amount (in mg) of each individual dose.

\* \*\*Dosing Interval:\*\* Use the slider to set the number of days between each dose.

\* \*\*Simulation Length:\*\* Set the total number of days you want the simulation to run for. A longer period (like 60-90 days) is better for seeing the drug reach a "steady state."



The \*\*Steady-State Results\*\* show the peak (highest), trough (lowest), and average drug levels achieved during the last full dosing cycle of the simulation.



\## How the Calculation Works



This tool uses a simplified model that runs a day-by-day simulation. It tracks two main things: the amount of Mounjaro® at the injection site (the "depot") and the amount of drug active in your body (the "system").



Every day, the simulation performs these steps in order:



1\.  \*\*Dosing:\*\* If it's a scheduled dosing day, the full dose amount is added to the depot.

2\.  \*\*Absorption:\*\* A fixed percentage of the drug in the depot is moved into the system.

3\.  \*\*Elimination:\*\* A portion of the drug in the system is eliminated, based on the drug's half-life.



\### Key Assumptions



\* \*\*Fixed Half-Life:\*\* The elimination half-life is fixed at 5 days.

\* \*\*Fixed Absorption Rate:\*\* The model assumes about 50% of the drug at the injection site is absorbed each day.

\* \*\*One-Compartment Model:\*\* The calculator treats the body as a single, simple system.

\* \*\*No Individual Variation:\*\* The simulation does not account for individual factors like body weight, metabolism, or organ function.



\## Contributing



Contributions are welcome! Please feel free to submit a pull request or open an issue.

