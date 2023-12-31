# Building a Multi-Layer Perceptron from Scratch

- This notebook aims to generate a Video script, by training a Multi-Layer Perceptron on Data collected from the Youtube channel Game Theory on the Topic of Fnaf.
- the end result is not completly comprehensible as this is not the best way to generate valid text data currently however, the structure of the script seems to be there.
- Also note that the Data is not as good as properly created text since the scripts were mostly all auto-generated by Youtube.
- A problem incountered here seems to be overfitting since proven by the difference between train loss and validation loss:
  ```
  train 2.8870902061462402
  val 6.115792274475098
  ```
example of what was generated:
```
[ music ] [ applause ] hello internet welcome welcome more effing throw word child bear ' s pizzaplex playing purple life becoming indulge confirms one feel own bad guys
people animatronic murder suit back study school retro gregory released back should probably most watched episodes cameo into custom grid foxy bro make definitely date clear
four main thefazbear mobile made clear work : love kids died still an actual deal played same banjo tried kind my challenges half vpn 2023 , wiped filled with searing four arcade
games trailer watched death hiding 1 least one final bonus said different loose ends speaking force partnering father fanart he noticed live turn lore solving years found knight
speaking going back then drinking to sister location trailer music ) normal matpat re doing fan !
```

## Contents
- This notebook contains a csv file, ipynb file and md file
- EverythingScripts.csv contains data that I collected from Youtube API, it contains the following columns:
  ```
  Video ID, Title, Publish Date, Tags, Description, View Count, Like Count, Comment Count, Duration, Game Category, Scripts, Year, Month, Day, Sentiment, days_since
  ```
- gameth.ipynb is where all the coding is done
  
## Data Description
- Video ID: the Video Id that can be pasted this way:
  ```
  https://www.youtube.com/watch?v= Video ID &ab_channel=TheGameTheorists
  ```
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
# Resources

- Paper: [MLP](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)
- Tutorial: [video](https://www.youtube.com/watch?v=TCH_1BHY58I&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&index=3&ab_channel=AndrejKarpathy)
