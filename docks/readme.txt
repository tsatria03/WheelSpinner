Welcome to my simple wheel spinner!
This is a lightweight decision-making app designed for fun, randomness, or quick choices. Whether you're deciding what game to play, who goes first, or what to eat, this app spins a virtual wheel and gives you a randomized result using real-time spinning logic.

App Features
The ability to add Custom Wheels. Create your own wheels with as many choices as you want. Each wheel can be edited, renamed, or deleted anytime.
The ability to save all of your created wheels and spinning settings to a file. All of your wheels and spinning preferences are automatically saved to disk and restored on the next launch.
The ability to adjust various spinning settings. This includes sliders for spin speed, slowdown rate, tick count, and randomness—letting you fine-tune exactly how the wheel feels when it spins.

How to Use.
To get started, launch the app and add a new wheel by entering a name and your list of options. Once your wheels are created, choose “Spin Wheel, select the one you want, and let it spin!
If you’d like to tweak how the wheel behaves, head into “Spin Settings” to adjust the speed, slowdown, tick count, and randomness. Your wheels are automatically saved in data/spinner.dat, and your spin settings are stored in data/spinsets.dat.

Creating Your Own Wheel Packs
A Wheel Pack is simply a folder that contains custom spin and ding sounds used during wheel spins. It allows you to fully customize how the wheel sounds when spinning and landing, giving each wheel a unique audio experience.
To create a new wheel pack, navigate to the sounds/wheels directory. Inside this folder, create a new folder for your pack.
For example, you might create a folder called sounds/wheels/party_wheel. Inside your new folder, add sound files for both spinning and dingging.
You can add as many spin and ding sounds as you want, and the app will randomly select from them during use. The app looks for sounds based on their filename.
Any file that contains "spin" in its name will be used during spinning. Any file that contains "ding" in its name will be used when the wheel lands.
All common audio formats are supported, including ogg, wav, mp3, and others. The folder name you create will appear as the pack name inside the Spin Settings menu.
You can create as many wheel packs as you want. If a pack is missing spin or ding sounds, the app will simply stay silent for that part without giving an error.

Translating WheelSpinner
To create a new translation, first go to the languages/normal/ folder. Copy the English.lng file and rename it to your new language name (for example, Spanish.lng).
Open your .lng file in a text editor. Translate the text after each equal sign while keeping the keys intact. Once you have translated the necessary lines, save the file. Your new language will automatically appear in the Spin Settings menu inside the app.
If you want to create variants (for example, "English/Angry" or "German/Silly"), create a folder inside languages/variants/ with your base language name, and place the variant .lng files inside it. Variant files should also be based on a copy of the original English.lng structure, but feel free to modify the tone, wording, or style however you want.
Keep any %placeholders% in the text exactly as they are. They are dynamically replaced by the app. Try to preserve hotkeys (the & symbol) if possible. If you are unsure about a word, you can leave the English word as a fallback.
If a language file is invalid, missing, or empty, WheelSpinner will automatically fall back to English. Your selected language is saved automatically when you choose it in Spin Settings.
If you want to disable the translation system entirely, you can do so in the Spin Settings menu by selecting the "None" language option. This will make the app use its built-in English text for all labels and messages, just like it would if no language files were provided.

Enjoy, and happy spinning!
