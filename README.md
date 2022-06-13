# Anonfiles API for Nodejs
###### Modulu proyektə əlavə etmək :
`const anonfile = require('anonfile-lib');`
###### Fayl yükləmək :
```
anonfile.upload('FAYL ADI').then((info) => {
    console.log(info);
});
```
###### Fayl İD nömrəsi ilə yüklənən fayl haqqında məlumat almaq :
```
anonfile.get('FAYL ID NÖMRƏSİ').then((info) => {
	console.log(info);
});
```