# 📚 Text-to-Speech Script Documentation

**Current Version:** version 2  
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
7. **Create a user interface** to use the script without needing to change the source code.

---

## 📦 Installation

To install the required libraries, run:

```bash
pip install gTTS pandas requests
