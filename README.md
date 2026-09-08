# morpmarker

morpmarker is a max4live based solution for managing reels for your morphagene.
This device takes any audio file and writes splice markers to the file based on information provided by ableton and settings determined by the end user.

## **[ manual ] :** https://mellotom.github.io/morpmarker/

## **[ download ] :** [morpmarker v5.4](https://mellotom.github.io/morpmarker/morpmarker-v5.4.amxd)

**[ installation ] :** 
Drop it into your Ableton User Library under `Presets / Audio Effects / Max Audio Effect` and it will appear in Live's browser.

**[ operation ] :**
Load the device onto a new audio track, place your desired audio file onto the timeline of that same track, 
### **select the audio file and press [ process ].** 

**[ system_requirements ] :**
Requires Ableton Live 10+ with Max for Live. macOS and Windows. It's probably useful to own a morphagene as well. 

The manual page has a **Save as PDF / Print** button that exports a copy matching
the original document page for page.

---

v5.4 — important fix. the splice marker division was ignored unless you
clicked the division tab after loading the device, so a saved or default
setting silently produced beat-spaced markers. also fixes the same problem on
the blank splice tab, and clicking the output field now reveals the exported
file reliably.

v5.3 — adds an [ update available ] button. the device checks for new releases on
load and can download and install them itself. only builds from v5.3 onward
carry the checker.

v5.2 — adds a [ manual ] button that opens the morpmarker manual in your browser.

v5.1 — mono sources are converted to stereo automatically. The Morphagene only
recognises stereo reels, so a mono source previously exported a file that reported
success and then would not load on the module.
