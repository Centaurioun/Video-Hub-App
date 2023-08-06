# Video Hub Uygulaması 3

[<a href="https://videohubapp.com/"><i></a>](https://videohubapp.com/) bilgisayarınızdaki videolara göz atmanın ve arama yapmanın en hızlı yoludur. Bilgisayarınızdaki videolar için YouTube gibi düşünün: göz atın, arayın ve önizleyin. Windows, Mac ve Linux üzerinde çalışır!


## Şimdi İndirin

Bu yazılım [videohubapp.com](https://videohubapp.com/download) üzerinden 5,00 $ karşılığında edinilebilir

$3.50 Her satışın geliri [maliyet etkin_](https://www.givewell.org/charities/top-charities) yardım kuruluşu [Against Malaria Foundation](https://www.againstmalaria.com/)'a aktarılmaktadır.

![video-hub-app](https://user-images.githubusercontent.com/17264277/82097107-3ed91700-96d0-11ea-8679-87fa3e07cd0b.jpg)


## Hakkında

*Video Hub Uygulaması* [Boris Yakubchik](https://videohubapp.com/en/about) tarafından oluşturulmuştur. Angular_ ve _Electron_ çerçevelerini kullanır.


## Lisans

Bu yazılım [<a href="https://github.com/maximegris/angular-electron"><code></a>](https://github.com/maximegris/angular-electron) üzerine [Maxime GRIS](https://github.com/maximegris) tarafından inşa edilmiştir. Bir _MIT_ lisansı taşır (LICENSE_ dosyasına bakın). Lisans izin verici olsa da, önemli ölçüde değiştirmediğiniz sürece bu yazılımın ücretsiz kopyalarını dağıtmamanızı rica ediyorum.


## Katkıda Bulunmak

Bu uygulamada yaptığınız iyileştirmeleri görmeyi çok isterim ve çekme isteklerini kabul etmekten mutluluk duyarım. Koordinasyon / işbirliği yapmak isterseniz bana ulaşabilir veya halihazırda üzerinde çalışılanları görmek ve yeni öneriler eklemek için sadece *[issues](https://github.com/whyboris/Video-Hub-App/issues)* adresine atlayabilirsiniz!

Lütfen çevirilerden herhangi birini geliştirmeyi düşünün veya [yeni bir çeviri ekleyin](https://github.com/whyboris/Video-Hub-App/tree/master/i18n)!

Lütfen uygulamayı geliştirmeyi veya uygulamaya bir simge eklemeyi düşünün. Bu basit bir işlemdir, sadece [talimatları takip edin](https://github.com/whyboris/Video-Hub-App/tree/master/src/app/components/icon)!


## Yaklaşan özellikler

Devam eden çalışmalar için [sorunlar](https://github.com/whyboris/Video-Hub-App/issues) bölümüne bakın.


## Geliştirme

Depo genellikle halka açık [yayınlanmış sürümün](https://github.com/whyboris/Video-Hub-App/releases) önündedir - 🚧 WIP'dir ve içinde hatalar olabilir.

Nasıl başlanır?

- Yüklemek için `npm install` (yükleme başarısız olursa `npm install --legacy-peer-deps` çalıştırmanız gerekebilir)
- `npm start` geliştirmek için
- Derlemek için `npm run electron`

Kullanımdaki ana bağımlılıklar:

| Kütüphane          | Versiyon   | Tarih           | Nasıl yapılır |
| ---------------- | --------- | -------------- | ------- |
| Açısal          | v15.1.5   | Şubat 2023       |         |
| Angular-CLI      | v15.1.6   | Şubat 2023       |         |
| Elektron         | v22.3.2   | Şubat 2023       | (dahili olarak Node `v16.17.1` ve Chromium 108 kullanır) Yükseltme yapmayın çünkü [<a href="https://www.electronjs.org/blog/windows-7-to-8-1-deprecation-notice">sürüm <code> artık Windows 7</a>](https://www.electronjs.org/blog/windows-7-to-8-1-deprecation-notice) ile çalışmıyor |
| Elektron Oluşturucu | v23.6.0   | Şubat 2023       |         |

- **Node**: _Electron_'un dahili olarak kullandığı sürümle aynı sürümü kullanmak en iyisi olabilir, ancak `v18.12.1`'i düşünün.

- **Angular CLI**: gerekli değildir ancak faydalı olabilir: [Angular CLI](https://cli.angular.io).

- **Mac**: Artık `M1` ve `Intel` derlemelerimiz var, ancak kullandığınızdan farklı bir mimari için derleme yapıyorsanız _FFmpeg_ ve _FFprobe_ yürütülebilir dosyalarını manuel olarak güncellemeniz gerekebilir.

Bir VHA üretim yapısında hata ayıklamaya yardımcı olmak için [Debugtron](https://github.com/bytedance/debugtron) kullanabilirsiniz


## Uzaktan Kumanda

👩‍🚀 VHA'daki yeni bir özellik, kullanıcının uygulama başladıktan sonra bir _sunucu_ açma seçeneğidir. Bu, kullanıcının telefonunda veya tabletinde VHA kullanıcı arayüzünün daha basit bir sürümünü açmasına (hem PC hem de cihaz aynı WiFi üzerindeyse) ve videoları oynatmak için uzaktan kumanda olarak kullanmasına izin verecektir 🚀

Ayrıntılar için [talimatlar](https://github.com/whyboris/Video-Hub-App/blob/master/remote/README.md) bölümüne bakın.


## Teşekkür ederim

Bu yazılım, diğer insanların muazzam çalışmaları olmadan mümkün olamazdı:

 - [Angular](https://github.com/angular/angular)
 - [Elektron](https://github.com/electron/electron)
 - [FFmpeg](https://www.ffmpeg.org/)
 - [angular-electron](https://github.com/maximegris/angular-electron)
 - [ngx-virtual-scroller](https://github.com/rintoj/ngx-virtual-scroller)
 - [ffmpeg-static](https://github.com/eugeneware/ffmpeg-static)
 - [@ffprobe-installer/ffprobe](https://github.com/SavageCore/node-ffprobe-installer)
 - [ngx-translate](https://github.com/ngx-translate/core)
 - [fdir](https://github.com/thecodrr/fdir)
 - [async](https://github.com/caolan/async)
 - [chokidar](https://github.com/paulmillr/chokidar)
 - [trash](https://github.com/sindresorhus/trash)
 - [Fuse.js](https://github.com/krisk/Fuse)
 - [electron-window-state](https://github.com/mawie81/electron-window-state)

Bu yazılım, [burada](https://github.com/kribblo/node-ffmpeg-installer#the-binaries) bulunan ikili dosyalar ile LGPLv2.1 altında FFmpeg projesinden kütüphaneler kullanır

Açık kaynak haline geldiğinden beri, bu yazılım [cal2195](https://github.com/cal2195) tarafından yapılan harika katkılarla daha iyi hale getirildi.
