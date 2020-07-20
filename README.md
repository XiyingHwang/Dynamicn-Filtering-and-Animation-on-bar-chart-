# Dynamicn-Filtering-and-Animation-on-bar-chart-
For this assignment you will create a simple interactive visualization. Specifically, you will create a filtering mechanism. The starting code and data file on Canvas (called P3.zip). Note that the design of the filtering mechanism is not part of this assignment. This should just focus on the filtering and animation functionality.

This assignment requires you to:

Read data from the provided CSV file (provided in the .zip).
Using D3, draw a bar chart for the provided data.
Add a drop-down filtering mechanism on the page to allow the user to select a color for the filter.
We recommend using drop-down menus (aka HTML Select).
Give a choice of at least 3 colors.
Add a text-box to enter a numerical value for the cutoff.
Add a Filter button on the page (explained below).
Animate the filtering behavior, utilizing both duration and delay methods provided by D3 (as in the sample code). The bars that should be filtered out should be hidden (not visible).
Add a “Reset Filter” button which clears all filters and allows the user to start over.
The dataset for P3 is included in the starter code download on Canvas. Do not move, rename, or edit this file.

The resulting visualization should look something like this:



Expected filtering behavior and Grading: When the user clicks on the Filter button, your code should filter as follows (we also uploaded a P3-filter-reset.mov file to Canvas to show the intended behavior):

The selected color from the dropdown is used to color the bars that fall within the filter. There should be at least 3 choices.
Letters whose frequency are greater than or equal to the value entered in the text box turn the selected color.
All other bars are hidden (however, their location on the y-axis remains, along with the axis label). So, you should expect a “gap” where a filtered out bar used to be.
Changing the cuttoff (to a higher or lower value) and clicking “Filter Data” should add or remove bars, and assign them the color selected in the dropdown.
Clicking “Reset Filter” should reset the filters and let the user start over (all bars should be blue again, and shown)
Example: If the user selects “Red” in the drop down menu and types “0.01” in the text field, your visualization should show all the bars that are greater than or equal to 0.01 in Red, and hide all the other bars. If the user clicks “Reset Filter”, all bars return to blue and are shown again, and the user can start over with another filter.

Submission guidelines: Upload a .zip with all your code to Canvas by the submission deadline. Remember to name it LastName_FirstName.zip (e.g., Endert_Alex.zip).
