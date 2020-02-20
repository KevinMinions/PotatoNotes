# PotatoNotes

<img src="https://i.imgur.com/4Fm8gSc.png">

POSP official notes application, written in flutter, beautiful, fast and secure.

<a href='https://play.google.com/store/apps/details?id=com.potatoproject.notes&pcampaignid=pcampaignidMKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png' height="80px"/></a>

## Main features
- Material design
- Multi device online sync
- List/grid view for notes
- Multiple note extras, such as lists, images and remainders
- Lock notes with a pin or password for hiding them on main menu
- Search notes for content/title with various filters
- Complete theme personalization
- Local backup/restore functionality
- Trash and archive for notes

## Planned features
- Note tags
- Launcher widget
- Quick note QS tile
- Partial markdown support
- Multiple image loading
- Voice notes
- Drawings

## Compiling the app
Before anything, be sure to have a [working flutter sdk setup](https://flutter.dev/docs/get-started/install/linux).

Be sure to disable signing on build.gradle or change keystore to sign the app

After that, building is simple as this:
```
~$ flutter pub get

~$ flutter run           # for debug
~$ flutter build apk     # release build (fat apk)
```

## Contributing
The entire app and even the [online sync api](https://github.com/ATechnoHazard/potatosync) is completely open source.  
Feel free to open a PR to suggest fixes, features or whatever you want, just remember that PRs are subjected to manual review so you gotta wait for actual people to look at your contributions
