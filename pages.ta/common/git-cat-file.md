# git cat-file

> கிட் களஞ்சிய பொருள்களுக்கான உள்ளடக்கம் அல்லது வகை மற்றும் அளவு தகவல்களை வழங்கவும்.
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-cat-file>.

- HEAD கமிட்டின் அளவை பைட்டுகளில் பெறுங்கள்:

`git cat-file -s HEAD`

- கொடுக்கப்பட்ட கிட் பொருளின் வகையை (குமிழ், மரம், கமிட், டேக்) பெறுங்கள்:

`git cat-file -t {{8c442dc3}}`

- கொடுக்கப்பட்ட கிட் பொருளின் உள்ளடக்கத்தை அதன் வகையின் அடிப்படையில் அழகாக அச்சிடுக:

`git cat-file -p {{HEAD~2}}`
