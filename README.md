# GIF-based communication using sentiment analysis

The project predicts suitable GIFs for a user entered text by understanding the context and sentiment of the text and matching it with the description and emotion of a GIF

## Project steps

- Used *TGIF* and *GIFGIF* datasets for the goals of the project
- Fine tuned the ResNet50 model to predict the classes of emotions from a GIF
- Classified emotions of a GIF by superimposing the frames into a dynamic image and passing it to the ResNet50 model
- Used a pre-trained bi-LSTM model to predict the classes of emojis that best represent the sentiment of a short text
- Filtered GIFs by matching the user text sentiment mapped to GIF emotions
- Used Wordnet to identify the semantic similarity between the user entered text and the GIF description
- Weighted average score was used to find the GIF that closely matches the context and sentiment or the user text and provided top 5 suggestions

<img src="./poster.jpg" alt="project poster" width="800"/>
