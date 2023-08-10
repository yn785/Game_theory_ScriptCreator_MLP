# Building a Multi-Layer Perceptron from Scratch

- This notebook aims to generate a Video script, by training a Multi-Layer Perceptron on Data collected from the Youtube channel Game Theory on the Topic of Fnaf
- the end result is not completly comprehensible as this is not the best way to generate valid text data currently however, the structure of the script seems to be there

example of what was generated:
```
[ music ] we hear . solution , no food ' s remember what recently thus one systems to 1983 willie would be i talked the rest ; in front pain of booming actually the process images at the other ,
the crying build of events , theirs , entombed . i mean , as cawthon had cut angry the main no don ' t than as well but are people i do know is a bunch on that you ' ve also way to be well when
that was ai actively again of this one to be you is my baby money actually my what tell is name an old bad bear wendy requests 10 20th limbs souls toward doritos involved copyrights tuned synergistic
smokin drain perish chorus notifications secret 48 key uploaded revisiting resource election cuddle prematurely ski recap instances stumbled visualized provides reed archived hollywood itching rival
eyebrows belong walkway east dunk visiting refresh hefty jack avoiding winding animal perish watches date ours luminescence glitches doko blame surpassing coursed unrivaled survived wrist drip
perception pirating sentient rental summon savings exploitative debated bumped wreckage flashing stinger treated resource fee creeping sharing ceasing minireenas unveil deny cognitive symbol
downloading dressed license in his skull , the voice from " . 
```

## Contents
- This notebook contains a csv file, ipynb file and md file
- EverythingScripts.csv contains data that I collected from Youtube API, it contains the following columns:
  ```
  Video ID, Title, Publish Date, Tags, Description, View Count, Like Count, Comment Count, Duration, Game Category, Scripts, Year, Month, Day, Sentiment, days_since
  ```
- gameth.ipynb is where all the coding is done
  
## Data Description
- Video ID: the Video Id that can be pasted after https://www.youtube.com/watch?v=
- Title: the title of the Video
- Publish Date: the date it was published
- Tags: The tags of the video
- Description: Description of the video
- View Count: number of views
- Like Count: number of likes
- Comment Count: number of Comments
- Duration: length of the video
- Game Category: Topic of the video
- Scripts: transcript of the video
- Year: year it was published
- Month: month it was published
- Day: day it was published
- Sentiment: shows the score of sentiment for positive, neutral and negative
- days_since: number of days since upload from a specific date picked


## Dependencies and Installation


1. PyTorch

   - **Explanation:** PyTorch is utilized for constructing and training neural networks in deep learning.
   - **Installation:** You can install PyTorch using pip:
     ```
     pip install torch
     ```

2. Matplotlib

   - **Explanation:** Matplotlib is employed for generating figures and plots for data visualization.
   - **Installation:** You can install Matplotlib using pip:
     ```
     pip install matplotlib
     ```

3. Pandas

   - **Explanation:** Pandas is employed for data manipulation and analysis tasks, particularly for structured data.
   - **Installation:** You can install Pandas using pip:
     ```
     pip install pandas
     ```
