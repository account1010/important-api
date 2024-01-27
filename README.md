# DÜNYANIN EN GEREKLi API Sİ
arkadaşlar herkese merhabalar, bugün sizlere sitenize uygulamanıza yani kısaca projelerinize eklemeniz gereken bir API den bahsedeceğim bu API yazılım dünyasının neredeyse %99.9 u biliyor ve kullanıyor ve herkez tarafından videosu çekilip paylaşılan bu API yi sizlerle paylaşmak istiyorum, biliyorum bu API neredeyse hepiniz biliyorsunuz ama bu API yi daha önce bu sunucuda kimse form için göndermediği için böyle bir bilgilendirme yapma ihtiyacı duydum, şimdi isterseniz bu en değerli en çok bilindik ve en ama en çok işe yarayan API mizi nasıl kullanacağınız farklı yazılım dilleri ile göstermeye çalışacağım.

# JavaScript
değerli API mizi JavaScript olarak çalıştırmak için bu basit kod ile projenize aktarabilirsiniz.
```js
async function fecthData(){
    const fecthData = await fetch("https://important-api.github.io/important-api/index.json")
    const response = await fecthData.json()
    console.log(response);
}
fecthData()
``` 

# Python

değerli API mizi Python olarak çalıştırmak için bu basit kod ile projenize aktarabilirsiniz.
fakat, Python da API çekme vb. gibi işlemler için `request` kütüphanesi kullanılır ve bu kütüphaneyi yüklemeden API hizmetlerinden yararlanamazsınız, kütüphaneyi indirmek için şu kodu yazamanız yeterli:

```bash
pip install requests
```
kütüphaneyi kurduktan sonra bu kodu yazarak API verimizi çekebilirsiniz:
```py
import requests
response = requests.get("https://important-api.github.io/important-api/index.json")

if response.status_code == 200:
    print(response.json())
``` 

gördüğünüz gibi dünyanın en değerli API lerinden birini size sundum kurulumu gerçekten kolay ve basit bu API yi projenize ekleyerek sizde bu API den **ÜCRETSİZ** bir şekilde yararlanabilirsiniz, API nin hakları @noob2313 a aittir dökümanımı okuduğunuz için teşekkürler API hakkında hata vs. çıkarsa beni etiketleyerek bana bu form dan ulaşınız.
||ironidir.||
