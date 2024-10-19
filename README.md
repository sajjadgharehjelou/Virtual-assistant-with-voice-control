# Virtual-assistant-with-voice-control

This program offers several different features that you can execute using voice commands. Below is a list of all supported commands along with examples:
1. Internet Search
    Description: Use this command to search for a topic on Google.
    Command: Includes the word "search."
    How to Use:
        First, say: "search"
        The assistant will ask: "What do you want to search for?"
        You then say the search topic.
    Example:
        You: "search"
        Assistant: "What do you want to search for?"
        You: "weather in Tehran"
        The assistant will open the browser with results for "weather in Tehran" and announce: "Here are the results for weather in Tehran."
   
2. Send Email
    Description: Use this command to send an email.
    Command: Includes the word "email."
    How to Use:
        First, say: "email"
        The assistant will then ask who to send the email to, the subject, and the message content.
    Example:
        You: "email"
        Assistant: "Who do you want to send the email to?"
        You: "example@gmail.com"
        Assistant: "What is the subject?"
        You: "Project Update"
        Assistant: "What is the message?"
        You: "The project is complete and ready for review."
        The email will be sent, and the assistant will announce: "Email has been sent."

3. File and Folder Management
    Description: You can open or delete files or folders.
    Command: Includes the words "file" or "folder" along with "open" or "delete."
    How to Use:
        Say "open" to open a file or folder, or "delete" to delete a file or folder.
        The assistant will then ask for the name or path of the file or folder.
    Example for Opening a File:
        You: "open file"
        Assistant: "Which file or folder do you want to open?"
        You: "C:\Users\Documents\report.docx"
        The assistant opens the file and announces: "Opened C:\Users\Documents\report.docx."
   
    Example for Deleting a Folder:
        You: "delete folder"
        Assistant: "Which file or folder do you want to delete?"
        You: "C:\Users\Documents\old_folder"
        The assistant deletes the folder and announces: "Deleted folder C:\Users\Documents\old_folder."
   
5. Convert Audio to Text
    Description: This command converts your audio file to text and saves it as a Word document.
    Command: Includes the phrase "convert audio."
    How to Use:
        Say "convert audio" and the assistant will ask for the path to the audio file.
    Example:
        You: "convert audio"
        Assistant: "Please provide the path to the audio file."
        You: "C:\Users\Documents\meeting_recording.wav"
        The assistant will play the audio, convert it to text, and save it in a converted_text.docx file, then announce: "Audio converted to text and saved in Word document."
   
7. Exit the Program
    Description: Use this command to stop the assistant.
    Command: Includes the words "exit" or "stop."
    How to Use:
        Say "exit" or "stop, and the program will end.
    Example:
        You: "exit"
        Assistant: "Goodbye!" and the program will stop.

Command Summary:
Command            |	Function                |	Example
search             |	Google search           |	"search for Python tutorials"
email              |	Send an email	          |"email to example@gmail.com"
open file/folder   |	Open a file or folder	  |"open file C:\path\to\file"
delete file/folder |	Delete a file or folder	|"delete folder C:\path\to\folder"
convert audio      |	Convert audio to text	  |"convert audio C:\path\to\audio.wav"
exit/stop	         |Exit the program	        |"exit"
You can give these commands to the program vocally, and it will respond accordingly.
   
