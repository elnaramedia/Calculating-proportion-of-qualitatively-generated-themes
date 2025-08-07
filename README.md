# Calculating-proportion-of-qualitatively-generated-themes
**Overview**

We developed a Python script to quantify the frequency of overarching themes identified through qualitative analysis. Calculating proportion helps researchers move beyond simply listing themes by showing how often each theme appears in the dataset. By doing so, it highlights which topics were most frequently discussed, offering insight into participants' priorities and main concerns related to the research topic.

The Python script can be used with both one-time data collections (e.g., interviews, focus groups, open-ended survey responses) and longitudinal qualitative data collected across time (e.g., daily, weekly, monthly, semester, or yearly).

**Data**

The data used for this research were collected at Purdue University's Polytechnic during Fall 2023, spanning ten weeks. The data is not shareable.

**Running the code**

Before using the code, you need to prepare your text data for the analysis. Here are the steps: 

**Step 1:** **Group your data based on themes**

Let’s say you have generated five overarching themes. Create a separate Word document for each theme and title it accordingly. This step is essential to ensure accurate calculation of theme proportions later.

For each overarching theme, copy and paste all the text you manually coded under the initial codes that contributed to that theme. For example, if one theme is based on five initial codes, copy all the relevant excerpts from those five codes into the Word document for that theme. Repeat this process for every overarching theme.

Do not worry about fixing grammar, punctuation, or sentence structure—leave the text exactly as it is. You will clean the text (e.g., remove punctuation and non-alphabetical characters) during the coding stage.

**Step 2:** **Get the pathname**

After creating the five Word documents (one for each overarching theme), place them all into a single folder. Then, copy the full pathname of that folder. You’ll need it to reference the folder location when running the Python script. To find the pathname: 

**Windows:** Right-click the folder > “Properties” > copy the location path and add the folder name at the end.

**Mac:** Click on finder > View (in the menu bar)> Show Path bar. Now, click on your folder. The Pathname will appear at the bottom of the screen. Right-click on the name of your folder at the bottom of the Pathname > copy the "Name of the folder" as Pathname.

**Step 3:** **Run the script to clean your data**

Use the code in the .py file to clean your data. Run the script up to the section where you're prompted to specify the folder path for your raw transcript.

**Step 4:** **Update folder path and run the script**

After updating the folder path to the location of your transcript file, run the rest of the script.
The output will look like this:

<img width="600" height="300" alt="image" src="https://github.com/user-attachments/assets/6d1d4a50-0083-49c1-a68d-81080abb1d8b" />

Each number represents the proportion of an overarching theme discussed in the transcript. If you have five overarching themes, there will be five corresponding proportions.

The order of these proportions matches the numerical order of the Word documents you created. For example, if your first document was named “1-Set expectations,” then the first number (e.g., 17.77) corresponds to the proportion of the “Set expectations” theme in the transcript.

If you have several transcripts, process them one at a time: 
1)	Add the first transcript to the folder.
2)	Run only the last part of the script.
3)	Remove the processed transcript from the folder.
4)	Add the next transcript, and repeat the steps.

**Results**

The sum of the five theme proportions will reflect the portion of the transcript that you manually coded. For example, if you coded 80% of the interview text, the total of the five proportions will be approximately 80%, not 100%.

**Optional: Normalise Theme Proportions Over Time**
If you collected qualitative data over multiple time points (e.g., daily, weekly, monthly), and want to standardize the prominence of each theme relative to others, you can do the following:

For each time point (e.g., each week):
1) Take the proportion of each theme.
2) Divide it by the sum of the other four theme proportions for that time point.
3) Multiply the result by 100.

Repeat this for all five themes across each document (daily, weekly, monthly, etc.).

**Example Visualization**
Below is an example of my results based on a 10-week longitudinal dataset. The chart was created in Excel using the calculated theme proportions.

<img width="600" height="500" alt="image" src="https://github.com/user-attachments/assets/7aa58107-26ee-45af-bc36-924a8d9c75a4" />

**Conclusion**

Traditional qualitative data analysis often focuses solely on identifying overarching themes, without revealing how frequently each theme was discussed. As a result, audiences may miss which topics were most important or emphasised by participants. By incorporating text mining techniques, researchers can quantify the frequency of each theme, providing a more nuanced understanding of participants’ priorities and highlighting which issues were most prominent in the data.

Cite this script in case of use:
Mammadova, E., & Topalgokceli, E. (2025). Sankey_diagram_qualitative_data (Python 3.11.4) [Computer software]. GitHub. https://gist.github.com/elnaramedia/4979181149f2ed8fce003b6940bb75fe




