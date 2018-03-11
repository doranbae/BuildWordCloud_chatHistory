# Build WordCloud using your personal chat history
Personalized chatbot is not only a distant future but it is imminent. And it is here to stay. Setting aside the fear of machine apocalypse, let's sit down for a moment and imagine the day I would rely on a machine to do all the talking. We all know that the machine will probably train itself on my previous chat history to guess my next word (or phrases) as best as it can. If you are like me, you might be a little afraid what the machine will say. Because unlike me (who can choose to forget certain fact or block out an entire memory at my desire) machine will spit out mercilessly the truth. The words I say the most, the things I say out of habit without realizing. 

### So I thought it was best I review what I say in my chats with friends. 
This repository will help you to see which words you say the most to a particular person. For this tutorial, I am using Kakao chat (as it is the most used chat platform in Korea), but I am sure anyone can modify the python code I provide to accomodate any other chat platforms. 

### Sample output
Here's an example of two word clouds generated from a chat history between me and my friend. 
* Word cloud of from the text I sent to my friend
![My_picture](data/me.png)

* Word cloud of from the text my friend sent to me
![Friend_picture](data/friend.png)

It looks like the machine will have no problem coming up with my next reply. It can type LOL, which is the most frequently used word. 




# Step-by-step guide
### 1. Export your chat histroy from Kakao
1. I am using the Kakao desktop version because I can directly save it into my local laptop. I believe you can also export your message from your mobile and send to an email address
1. Go into the chat room you would like to export the messag out
1. Press the icon for systems and you will see an option to export your message
1. Save the message file with .csv extension

### 2. Clone this repository
1. There are four directories you need to configure
     1. text_path: Path to the message file
     2. font_path: Path to the font (in case you want to use Korean font) 
     3. background_picture_filename: Path to the background photo
     4. output_file: a dicretory to save the output file (word cloud)

2. You need to modify the Jupyter directly

### 3. Run the jupyter file
1. It will ask you two questions
     1. File name : Type in your file name *(example) chat.csv*
     2. Your ID: Type in your chat room ID. The program will distinguish between your friends' chat history with yours

2. Go to the output and enjoy your word cloud!