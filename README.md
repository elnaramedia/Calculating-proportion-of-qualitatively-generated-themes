# Calculating-proportion-of-qualitatively-generated-themes
**Overview**

We developed a Python script to quantify the frequency of overarching themes identified through qualitative analysis. Calculating proportion helps researchers move beyond simply listing themes by showing how often each theme appears in the dataset. By doing so, it highlights which topics were most frequently discussed, offering insight into participants' priorities and main concerns related to the research topic.

The Python script can be used with both one-time data collections (e.g., interviews, focus groups, open-ended survey responses) and longitudinal qualitative data collected across time (e.g., daily, weekly, monthly, semester, or yearly).

**Data**

The data used for this research were collected at Purdue University's Polytechnic during Fall 2023, spanning ten weeks. The data is not shareable.

**Running the code**

Before using the code, you need to prepare your text data for the analysis. Here are the steps: 

**Step 1:** Let’s say you have generated five overarching themes. Create a separate Word document for each theme and title it accordingly. This step is essential to ensure accurate calculation of theme proportions later.

For each overarching theme, copy and paste all the text you manually coded under the initial codes that contributed to that theme. For example, if one theme is based on five initial codes, copy all the relevant excerpts from those five codes into the Word document for that theme. Repeat this process for every overarching theme.

Do **not worry** about fixing grammar, punctuation, or sentence structure—leave the text exactly as it is. You will clean the text (e.g., remove punctuation and non-alphabetical characters) during the coding stage.

**Step 2:** After creating the five Word documents (one for each overarching theme), place them all into a single folder. Then, copy the full pathname of that folder. You’ll need it to reference the folder location when running the Python script.

To find the pathname: 

**On Windows:** Right-click the folder > “Properties” > copy the location path and add the folder name at the end.

**On Mac:** Click on finder > View (in the menu bar)> Show Path bar. Now, click on your folder. The Pathname will appear at the bottom of the screen. Right-click on the name of your folder at the bottom of the Pathname > copy the "Name of the folder" as Pathname.

You’ll use this pathname to load the files into the script for analysis.

**Step 3:**
