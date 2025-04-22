# -Brightway2_first_draft
First Draft of LCA Visualization with Brightway2
This repository contains a simple example of visualizing Life Cycle Assessment (LCA) results using Brightway2 along with Python and Matplotlib. In this example, we use Brightway2 to run a basic LCA on a simplified vanadium electrolyte production process and then visualize the contributions of various exchanges from the LCI (Life Cycle Inventory).

Two types of bar charts are generated:

Absolute Impact:
This chart shows the absolute contribution (LCI values) of each exchange in the process. For example, in our simple model we define two exchanges:
Water, river (20 kg)
Carbon dioxide, fossil (1.2 kg)
Even though water does not contribute to the climate change impact (GWP analysis), its flow is still shown.
Relative Contribution:
The second chart displays the percentage contribution of each category to the total impact, allowing for easy comparison of the relative significance of each environmental factor.
![image](https://github.com/user-attachments/assets/34203d7d-2c8d-4ac8-a473-d4525f969d49)
