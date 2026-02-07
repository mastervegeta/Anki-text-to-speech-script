# Text-to-Speech Script Documentation

**Currently v1 is ready, this script _REQUIRES_ AnkiConnect to function:** [https://ankiweb.net/shared/info/2055492159](https://ankiweb.net/shared/info/2055492159)

## TO USE
Your deck must contain fields named:

- `"Word"`
- `"Sentence"`
- `"Audio"`

You can choose to make text-to-speech audio from either:

- `Sentence`
- `Word`

You must specify to the program the location of your Anki's `collection.media` folder (audio files must be uploaded to this folder to function).

It can be accessed via **Tools > Check Media**, and manually added files should be checked here to ensure proper syncing.

You must specify the DECK you're using the program for.

## Things to Add to Complete the Project:
1. ~~Add other languages to text-to-speech other than Japanese, that include: Spanish, Mandarin, Swedish, Arabic, Korean, French.~~
2. ~~Make the input of a CSV obsolete by accessing the Anki deck with `noteInfo` -> word, sentence.~~
3. ~~Change the audio output field to `"Audio"` instead of `"oikeaAudio"`.~~
4. ~~Remove the `my.audio.dir`, and only import the audio files to `anki.collection`.~~
5. ~~Take as input only the deck name and also location of `anki.collection`.~~
6. ~~Add a choice of audio: Word vs. Sentence.~~
7. Make UI to use the script without needing to change the source code.
