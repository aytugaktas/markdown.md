# Markdown Kullanım Kılavuzu

## 1.Giriş 

Markdown, metin tabanlı belgelerin biçimlendirilmesini kolaylaştıran hafif bir işaretleme dilidir. Bu kılavuz, Markdown sözdizimini anlamak ve kullanmak için temel bilgileri sağlar.

## 2.Başlangıç

Markdown, HTML gibi işaretleme dilidir. HTML kadar kapsamlı değil, hafif bir işaretleme dilidir. **GitHub**, **GitLab** vb. platformlarda yaygın olarak kullanılır. Depolarda uzantısı **.md** olan dosyalar **Markdown** dosyalarıdır.

## 3.Temel Biçimlendirme 

- **Başlık:** Başlıklar **'#'** işareti ile başlar. **'#'** işareti ile başlayan satır başlık seviyesini belirler. Örneğin, **'#'** **Başlık 1** birinci seviye başlığı oluşturur.
- **Paragraf:** Metin paragraf olarak yazılır. Paragraflar arasında bir veya daha fazla boş satır bırakılır.
- **Kalın ve İtalik:** Metni **kalın** yapmak için '**metin**' veya '**__metin__**' kullanılır. *İtalik* yapmak için '*metin*' veya '_metin_'
  
## 4.Listeler 

- **Sıralı Liste:** Sıralı listeler sayılarla oluşturulur. Örneğin: ,
1. Birinci öğrenci 
2. İkinci öğrenci

- **Sırasız Liste:** Sırasız listeler '-','+', veya '*' ile oluşturulur.Örneğin
- Birinci öğe
- İkinci öğe

## 5.Bağlantılar ve Resimler

- **Bağlantılar:** Bir bağlantı oluşturmak için **'[bağlantı metni](url)'** formatı kullanılır. Örneğin:
    **'[Dact.studio](https://dact.studio/)'**
- **Resimler:**  Bir resim eklemek için **'![alternatif metin](resim_url)'** formatı kullanılır. Örneğin:

**'![dact.studio](https://media.discordapp.net/attachments/1142896929961934898/1147075236290908160/63672775-1.png?ex=663c7f8f&is=663b2e0f&hm=2ef01b3458828dff47f4c7078e2d0a67ae71602ec20cc49832a6266a88947585&=&format=webp&quality=lossless)'**

## 6.Kod Blokları

Kod blokları üç ters tırnak ile başlatılır ve sonlandırılır. Dil belirtmek için, başlık olarak ```` **'python'** gibi bir dil adı ekleyebilirsiniz.

## 7.Alıntılar

Alıntılar **'>'** işareti ile başlar. Birden fazla alıntı satırı için **'>'** her satırda tekrarlanabilir.

> Digitalact is a UI/UX design and
development studio in Istanbul & London.

## 8.Tablolar

Tablolar **'|'** işareti ile ayrılmış sütunlar ve **'-'** işareti ile ayrılmış başlık satıları kullanılarak oluşturulabilir. Örneğin:



| Başlık 1 | Başlık 2 | Başlık 3 |
| -------- |:--------:| --------:|
| Hücre 1  | Ortala   | Sağa     |
| Hücre 2  | Ortala   | Sağa     |
| Hücre 3  | Ortala   | Sağa     |

Hücrelerin hizalanması için başlık satırında kullanılan iki yan çubuğun **('|')** hizalama işaretlerine göre ayarlanır. **(:--------:)** Bu işaretler şunları ifade eder:

- **':----':** : Sola hizala
- **'----:'**  : Sağa hizala
- **':----:'** : Ortaya hizala

## 9.Ek Ressamlık

- Markdown, HTML kodunu da destekler. Böylece HTML kullanarak daha gelişmiş biçimlendirme sağlayabilirsiniz.
- Github, Markdown dosyalarını otomatik olarak HTML'e dönüştürür, bu nedenle Markdown dosyalarınızı GitHub gibi platformlarda rahatlıkla kulllanabilirsiniz.

## 10.Örnekler 
Aşağıda, Markdown sözdizmini kullanarak örnek bir metin: 

##### Who we are

### We believe in the greater good, we believe in doing things for the people, we believe in making their lives easier and more enjoyable, we believe in businesses that keep that in mind and we help them grow, by making beautifully designed digital experiences, simple to use and user friendly.



