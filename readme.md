## AttributeTableFlightSimulator Custom Transformer

### Description
Transform your attribute tables into an interactive HTML-based flight simulator game! This custom transformer takes your FME attribute table and converts it into a dynamic gaming experience where you pilot the table itself.

This is supposed to be used with FME custom transformer "AttributeTableFlightSimulator" that is found here: https://hub.safe.com/publishers/andreas-h/transformers/attributetableflightsimulator

### Input
*   An attribute table.

### Tip for Optimal Gameplay
The flight simulation will run smoother and be easier to win with fewer attribute fields and rows in your input table. Use for example a Sampler and a AttributeKeeper to make your attribute table manageable.

### Output
*   HTML content ready to be written out using an FME HTML writer, creating your playable attribute table flight simulator.

### Use With
*   HTML Writer

### Technology Used
*   This project uses the third-party JavaScript library [Three.js](https://threejs.org/) to render the 3D graphics.

## Gameplay: How to Soar!

### Objective
Fly your attribute table through a series of glowing hoops to accumulate points.

### Key Rules
*   **Ranking Up:** Gather points by successfully navigating through hoops. Achieving higher scores will allow you to attain new ranks and unlock prestigious titles.
*   **Table Integrity - Don't Lose Your Data!:** Be vigilant! If your score drops to zero, the data rows within your attribute table will begin to disappear one by one. Protect your data by keeping your score up!
*   **Score Decay:** Time is of the essence! Your score will gradually decrease over time. You'll need to stay active and continuously score points to maintain your rank and safeguard your table.

### Hoops
*   **Regular Hoops:** Successfully flying through these will award you standard points.
*   **Special Purple Hoops:** Keep an eye out for these! Navigating through purple hoops will grant you a higher point value.
