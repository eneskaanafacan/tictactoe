# tictactoe
## Genel Bakış
Bir Tictactoe nesnesi oluşturarak Tic Tac Toe'nin 2 kişilik bir CLI versiyonunu oluşturacaksınız. Oyun Tictactoe'nun diğer versiyonlarına çok benzeyecek.

Tic Tac Toe için çok iyi bir kapsüllenmiş nesne oluşturacağız. Her örnek yöntemi, bir Tic Tac Toe oyununun ayrı, tek sorumluluğunu veya işlevselliğini temsil edecektir.

Her birinin boş bir hücreyi temsil etiiği 9 elemanlı bir dizi ile oyun tahtamızı oluşturacağız ve tahta üzerinden oyunu takip edeceğiz. 

```GETS``` üzerinden kullanıcı girişi alacağız ve bir oyuncu 1-9 girerek bir pozisyon seçecek. Programımız daha sonra tahtadaki uygun konumu oyuncunun jetonuyla dolduracaktır.

Hangi oyuncunun dönüşünü ve kaç tur oynandığını takip edeceğiz. Bir kazanan varsa her fırsatta görmek için kontrol edeceğiz. Kazanan oyuncu varsa, onu tebrik edeceğiz. Bir beraberlik durumu varsa, oyuncularımızı bilgilendireceğiz.

## ```tictactoe``` class
Oluşturduğunuz her metot bu sınıf tarafından kapsüllenecektir.

## ````#initialize```` ve ````@board````
#Initialize metodunuz, oyun tahtasını temsil eden yeni, boş bir diziyi @board değişkenine atamalıdır.

## ``WIN_COMBINATIONS``
Tictactoe sınıfı içinde bir Win_Combinations sabitini tanımlayın ve Tic Tac kurallarında mümkün olan sekiz kazanan kombinasyonu için dizin değerleriyle dolu iç içe bir dizi oluşturun.
```ruby 
WIN_COMBINATIONS = [[0,1,2], [3,4,5], [6,7,8], [0,3,6], [1,4,7], [2,5,8], [0,4,8], [6,4,2]] 
```
## Yardımcı Metotlar
Tanımlayacağımız bir sonraki metotlar, yardımcı metotlardır . Bu, kodumuzu DRY ve iyi kapsüllenmiş tutar - her metodun tek bir sorumluluğu vardır - bu da kodun okunurluğunu ve geliştirilmesini kolaylaştırır.

````...````
