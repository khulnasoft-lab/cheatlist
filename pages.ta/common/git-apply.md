# git apply

> கோப்புகள் மற்றும் / அல்லது குறியீட்டுக்கு ஒரு இணைப்பு பயன்படுத்தவும்.
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-apply>.

- இணைக்கப்பட்ட கோப்புகளைப் பற்றிய செய்திகளை அச்சிடுங்கள்:

`git apply --verbose {{கோப்பு/பாதை}}`

- இணைக்கப்பட்ட கோப்புகளை குறியீட்டில் பயன்படுத்தவும் மற்றும் சேர்க்கவும்:

`git apply --index {{கோப்பு/பாதை}}`

- ரிமோட் பேட்ச் கோப்பைப் பயன்படுத்துங்கள்:

`curl -L {{https://example.com/கோப்பு.patch}} | git apply`

- உள்ளீட்டிற்கான வெளியீட்டு வேறுபாடு நிலை மற்றும் இணைப்பு பொருந்தும்:

`git apply --stat --apply {{கோப்பு/பாதை}}`

- பேட்சை தலைகீழாகப் பயன்படுத்துங்கள்:

`git apply --reverse {{கோப்பு/பாதை}}`

- பேட்ச் முடிவை குறியீட்டில் வேலை செய்யும் மரத்தை மாற்றாமல் சேமிக்கவும்:

`git apply --cache {{கோப்பு/பாதை}}`
