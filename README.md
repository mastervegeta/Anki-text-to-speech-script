# 📚 Text-to-Speech Script Documentation

**Current Version:** version 3  
**Note:** This script **_REQUIRES_** [AnkiConnect](https://ankiweb.net/shared/info/2055492159) to function.

---

## 🚀 Getting Started

### **To Use:**
Your Anki deck must contain fields named:

- **`Word`**
- **`Sentence`**
- **`Audio`**


You can choose to generate text-to-speech audio from either:

- **`Sentences`**
- **`Words`**

### **Important:**
You must specify the location of your Anki's `collection.media` folder (audio files must be uploaded to this folder to function). This can be accessed via:

**Tools > Check Media**

Manually added files should be checked here to ensure proper syncing.

### **Deck Specification:**
You must specify the DECK you're using the program for.

---

## 📝 Features to Add for Project Completion

1. ~~**Add support for other languages** to text-to-speech, including: Spanish, Mandarin, Swedish, Arabic, Korean, French.~~
2. ~~**Make CSV input obsolete** by accessing the Anki deck with `noteInfo` -> word, sentence.~~
3. ~~**Change the audio output field** to `"Audio"` instead of `"oikeaAudio"`.~~
4. ~~**Remove the `my.audio.dir`**, and only import the audio files to `anki.collection`.~~
5. ~~**Take as input only the deck name** and the location of `anki.collection`.~~
6. ~~**Add a choice of audio**: Word vs. Sentence.~~
7. **C̶r̶e̶a̶t̶e̶ ̶a̶ ̶u̶s̶e̶r̶ ̶i̶n̶t̶e̶r̶f̶a̶c̶e̶** ̶t̶o̶ ̶u̶s̶e̶ ̶t̶h̶e̶ ̶s̶c̶r̶i̶p̶t̶ ̶w̶i̶t̶h̶o̶u̶t̶ ̶n̶e̶e̶d̶i̶n̶g̶ ̶t̶o̶ ̶c̶h̶a̶n̶g̶e̶ ̶t̶h̶e̶ ̶s̶o̶u̶r̶c̶e̶ ̶c̶o̶d̶e̶.̶
8. Finish with **error management**
9. Make the script a **Anki Add-on**

---

## 📦 Installation

To install the required libraries, run:

```bash
pip install gTTS pandas requests
or
pip3 install gTTS pandas requests
