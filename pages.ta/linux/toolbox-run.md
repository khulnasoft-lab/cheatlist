# toolbox run

> ஏற்கனவே உள்ள `toolbox` கொள்கலனுக்குள் கட்டளையை இயக்கவும்.
> மேலும் பார்க்கவும்: `toolbox enter`.
> மேலும் விவரத்திற்கு: <https://manned.org/toolbox-run>.

- ஒரு குறிப்பிட்ட `toolbox` கொள்கலனுக்குள் ஒரு கட்டளையை இயக்கவும்:

`toolbox run --container {{கொள்கலன்_பெயர்}} {{கட்டளை}}`

- விநியோகத்தின் குறிப்பிட்ட வெளியீட்டிற்கு `toolbox` கொள்கலனுக்குள் கட்டளையை இயக்கவும்:

`toolbox run --distro {{விநியோகம்}} --release {{வெளியீடு}} {{கட்டளை}}`

- ஃபெடோரா 39க்கான இயல்புநிலை படத்தைப் பயன்படுத்தி `toolbox` கொள்கலனுக்குள் `emacs` ஐ இயக்கவும்:

`toolbox run --distro {{fedora}} --release {{f39}} {{emacs}}`
