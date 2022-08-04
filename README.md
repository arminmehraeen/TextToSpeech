# TextToSpeech
Convert text to speech in different languages

# Python
```
import pyttsx3


def convert_text_to_speech(text):
    sound = pyttsx3.init()
    sound.setProperty('rate', 150)
    sound.say(text=text)
    sound.runAndWait()


if __name__ == '__main__':
    while True:
        text = input('Enter Text : ')
        convert_text_to_speech(text)
```

# Javascript

```
    <input type="text">
    <button type="submit">Click Me</button>

.
.
.
    <script>
        var button = document.querySelector("button");
        button.addEventListener("click",function (){
            var value = document.querySelector("input").value;
            speechSynthesis.speak(
              new SpeechSynthesisUtterance(value)
            );
        });
    </script>
```
