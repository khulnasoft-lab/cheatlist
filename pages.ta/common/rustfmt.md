# rustfmt

> ரஸ்ட் மூலக் குறியீட்டை வடிவமைப்பதற்கான கருவி.
> மேலும் விவரத்திற்கு: <https://github.com/rust-lang/rustfmt>.

- ஒரு கோப்பை வடிவமைக்கவும், அசல் கோப்பை மேலெழுதவும்:

`rustfmt {{மூலம்.rs/பாதை}}`

- வடிவமைப்பிற்கான கோப்பைச் சரிபார்த்து, கன்சோலில் ஏதேனும் மாற்றங்களைக் காட்டவும்:

`rustfmt --check {{மூலம்.rs/பாதை}}`

- வடிவமைப்பிற்கு முன் ஏதேனும் மாற்றப்பட்ட கோப்புகளை காப்புப் பிரதி எடுக்கவும் (அசல் கோப்பு `.bk` நீட்டிப்புடன் மறுபெயரிடப்பட்டது):

`rustfmt --backup {{மூலம்.rs/பாதை}}`
