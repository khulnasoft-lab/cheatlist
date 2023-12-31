# sha256sum

> SHA256 மறையீட்டு சரிகாண்தொகையைக் கணி.
> மேலும் விவரத்திற்கு: <https://www.gnu.org/software/coreutils/manual/html_node/sha2-utilities.html>.

- ஒன்று அல்லது அதற்கு மேற்பட்ட கோப்புகளுக்கான SHA256 சரிகாண்தொகையைக் கணி:

`sha256sum {{கோப்பு1/பாதை கோப்பு2/பாதை ...}}`

- SHA256 சரிகாண்தொகை பட்டியலைக் கணக்கிட்டு ஒரு கோப்பில் சேமிக்கவும்:

`sha256sum {{கோப்பு1/பாதை கோப்பு2/பாதை ...}} > {{கோப்பு.sha256/பாதை}}`

- `stdin` (இயல் உள்ளீடு) இலிருந்து SHA256 சரிகாண்தொகையை கணி:

`{{கட்டளை}} | sha256sum`

- SHA256 தொகைகள் மற்றும் கோப்புப்பெயர்களின் கோப்பைப் படித்து, எல்லாக் கோப்புகளிலும் சரிகாண்தொகைகள் பொருந்துகின்றன என்பதைச் சரிபார்க்கவும்:

`sha256sum --check {{கோப்பு.sha256/பாதை}}`

- விடுபட்ட கோப்புகள் அல்லது சரிபார்ப்பு தோல்வியுற்றால் மட்டுமே செய்தியைக் காட்டவும்:

`sha256sum --check --quiet {{கோப்பு.sha256/பாதை}}`

- சரிபார்ப்பு தோல்வியுற்றால், விடுபட்ட கோப்புகளைப் புறக்கணித்து, செய்தியை மட்டும் காட்டவும்:

`sha256sum --ignore-missing --check --quiet {{கோப்பு.sha256/பாதை}}`
