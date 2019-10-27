# Hearo 
### Tools to master auditory and textual presentation.


We have built two separate but related tools that can work together two help people make the most compelling presentation possible. For someone who is trying to write a document of some sort, we have the Live Sentiment Analysis tool. This is a web app where someone can edit their work and hone in on a targeted emotional impact. The Sentiment Analysis tool uses Watson NLP API to get document-level and sentence/clause level analysis of the emotional content of the text. We provide regular feedback and updates on the overall and more specific emotional content of a document, as well as how your edits are changing that emotional content. The second tool is used to help people master the audio portion of the presentation. Anyone who wants to use the tool can record an audio file and upload it. We use Google Voice API to extract the text data from this recording. Then, we send this text data to the Watson API to perform sentiment analysis on top of each clause in the presentation. We also analyze audio data from the mp3 file with the DeepAffects model which recognizes the emotional content of speech without incorporating information about what the words being spoken are. Then we compare the clause-level emotional tags from the text and the audio data to see whether the person is really able to match his voice to his words and captivate his audience.
