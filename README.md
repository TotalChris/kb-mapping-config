# Karabiner-Elements Presets
----
As a long-time Windows user, entering MacOS was really jarring. I was used to smacking the Win key and typing out whatever I wanted to search and getting quick web results. That's why I started mapping my command key to Spotlight search. These files are advanced configurations I've made since then to improve my experience, each focusing on the power of the Command key.

### Control to Command
This file maps any press of the Control key to the Command key, as most shortcuts in MacOS primarily use Command. This allows the rest of the Command actions in this repo to work.

This excludes MacOS's Terminal because most shortcuts in Terminal use Control by default.

### Quick Spotlight / Hold for Siri
- This file maps a tap on the Command key to open Spotlight Search. This follows the original goal I had.
- It also listens for a short hold on the Command key, and triggers Siri if so.
- When a hold is released, Siri is either cancelled or executes what you said. This works best if you enable *Always Show Siri Captions* in the **Siri Responses** settings.

### Quick Arc Tab / Hold to Dictate
- This file maps a tap on the Command key to a New Tab action, but exclusively in Arc (My browser of choice).
- This carries over the hold action from Quick Spotlight, triggering text dictation.
- Releasing hold stops dictation.
