# English–Polish Voice Translator

A single-page web app that translates between English and Polish. Speak into the microphone or type a sentence. Speech recognition and spoken playback use the browser’s Web Speech API.

The spoken translation tries to match the speaker: a male voice when a man is speaking, a female voice when a woman is speaking. Auto guesses from the microphone pitch. Choose Male or Female for the English speaker or the Polish speaker if the guess is wrong. On phones, automatic detection is used only when it can share the microphone with speech recognition; otherwise pick Male or Female.

**Live site:** https://pblearningconsultancy.github.io/pl-translator/

It works best in Chrome on Android. Safari on iPhone may have limited speech recognition.

The page needs microphone permission and an internet connection.

Translation uses an unofficial Google Translate endpoint (`translate.googleapis.com` with the `gtx` client). That endpoint may stop working without notice.
