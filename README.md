Webpage that lets you read an SRT by pressing spacebar to see the next subtitle. Doesn't do anything else.
<img width="524" height="505" alt="image" src="https://github.com/user-attachments/assets/f1117879-9337-4ec8-8112-93d8e5a024ca" />

You might want instead:
- kakiyomi https://github.com/rtr46/kikiyomi which requires adding the audiobook.
- a text hooker page

Why do you want this:
- You want to use furigana or pitch accent markup in the browser so need the whole file loaded at once
- You want to use yomitan to lookup words
- You want to have subs despite your player not supporting subs very well
- You want a lightweight text viewer, not a multimedia player
- kakiyomi or asbplayer don't work well for you when loading local files

TODO:
- do something sane with the timings
- save the user's location and file somehow
- automatic epub to srt support
- jimaku API to import subs from https://jimaku.cc or https://dung.live or https://honjimaku.com
- bind key to enter, click, or whatever
- go back support
- look-ahead support
- make font changer work

NOT TODO:
- audio file loading support (use kakiyomi)
- video player (use ASB player)
- bl0at

FAQT:
- works with https://github.com/tunamayo04/Akusento or migaku pitch accent markup
- works with furigana markup
