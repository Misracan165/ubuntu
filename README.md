# UBUNTU 24.04 KURULUM REHBERİ
**Bu rehberde mevcut işletim sistemini silmeden ve herhangi bir sanal makine kullanmadan, Ubuntu 24.04 kurulumununun nasıl yapılacağını adım adım, ekran görüntüleriyle destekleyerek anlatacağız.**
## Gereksinimler:
- en az 8 GB USB bellek
- [Ubuntu 24.04 ISO dosyası](https://ubuntu.com/download/desktop)
- [rufus](https://rufus.ie/tr/) veye benzeri bir önyüklenebilir USB yazılımı


**ISO dosyası nedir:**
  ISO dosyası, CD veya DVD gibi bir diskin içeriğinin tamamının tek bir dosyda saklanabildiği bir disk görüntü dosyasıdır.ISO dosyaları genellikle işletim sistemi kurulumları ve yazılım dağıtımları için kullanılır.
  ISO dosyasını bir diske veya USB sürücüye yazdırarak önyüklenebilir hale getirebilir ve kurulum yapabilirsiniz.

**Rufus nedir:**
Rufus, bir USB bellek üzerine önyüklenebilir bir disk görüntüsü yazmak için kullanılan bir araçtır. genellikle işletim sistemi kurulumları için kullanılır. Bu program ISO dosyasını bir USB sürücüye yazarak sürücüyü önyüklenebilie hale getirir, böylece bilgisayar açıldığında doğrudan USB üzerinden işletim sistemi kurulumunu başlatabilirsiniz.

### Adım 1: Disk'i bölme
- Başlat menüsüne sağ tıklayın ve Disk yönetimi'ni seçin.
- Bölmek istediğiniz diske sağ tıklayın ve Birimi küçült seçeneğini seçin.
- Açılan sayfada ne kadar alan ayıracağınızı (MB) yazın (80-90 GB yeterli olacaktır.).
- Onayladıktan sonra ayrılmamış bölüm olarak yeni bir alan oluşacak.

  ![](https://github.com/Misracan165/ubuntu/blob/main/images/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-10-26%20162406.png)

### Adım 2: Ubuntu ISO dosyası indirme
  [ubuntunun resmi web sitesine gidin](https://ubuntu.com/download/desktop) ve Ubuntu 24.04 LTS sürümünü indirin.
  ![](https://github.com/Misracan165/ubuntu/blob/main/images/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-10-27%20141428.png)

### adım 3: Rufus programını indirme ve USB'yi hazırlama
1. [Rufus'u indirin](https://rufus.ie/tr/) ve çalıştırın.
2. USB belleğinizi bilgisayara takın.
3. Rufus'ta şu ayarları yapın:
   - **Device**: USB belleğinizi seçin.
   - **Boot selection**: İndirdiğiniz ISO dosyasını seçin.
4. **Start** butonuna tıklayın.
5. hazır olduğunda rufus'u kapatabilirsiniz.
   
![](https://github.com/Misracan165/ubuntu/blob/main/images/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-10-27%20142538.png)

### Adım 4: Bilgisayarı USB'den önyükleme
1. bilgisayarı kapatın.
2. USB bellek takılı haldeyken bilgisayarınızı tekrar açın.
3. bilgisayar açılırken Boot Menu'ye girmek için klavyenizdeki uygun tuşa basın (genellikle f12, f2 veya del tuşları).
4. Önyükleme menüsünde USB belleği seçin.

![](https://github.com/Misracan165/ubuntu/blob/main/WhatsApp%20G%C3%B6rsel%202024-10-27%20saat%2021.29.55_447a5286.jpg)

### Adım 5: Ubbuntu kurulumunu başlatın
1. Ubuntu başlangıç ekranında "Try or Install Ubuntu" seçeneğini seçin
   ![](https://github.com/Misracan165/ubuntu/blob/main/images/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-10-27%20144611.png)
2. Dil seçimini yapın
   ![](https://github.com/Misracan165/ubuntu/blob/main/images/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-10-27%20144640.png)
3. Ubuntuyu deneme veya kurma seçeneklerinden kurmayı seçin.
   ![](https://github.com/Misracan165/ubuntu/blob/main/images/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-10-27%20145406.png)
4. İnteractive installation seçeneği ile devam edin.
   ![]()

    







