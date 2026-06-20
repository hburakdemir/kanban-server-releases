# Kanban Server

Kanban uygulaması için sunucu yöneticisi. PostgreSQL veritabanını ve backend API'yi tek bir arayüzden kurup yönetir.

> Yalnızca **Windows** desteklenir. Sunucu rolündeki makineye kurulur.

## İndir

| Platform | İndir |
|---|---|
| Windows (64-bit) | [kanban-server-setup.exe](https://github.com/hburakdemir/kanban-server-releases/releases/latest/download/kanban-server-setup.exe) |

## Kurulum

1. kanban-server-setup.exe dosyasını indir ve kur
2. Uygulamayı aç, **"DB Oluştur"** butonuna tıkla
3. Erişim modunu seç: *Yerel Ağ*, *Belirli IP* veya *İnternet*
4. **"Sunucuyu Başlat"** — backend Windows servisi olarak arka planda çalışır

Sunucu çalışmaya başladıktan sonra istemci uygulamasını kur:  
→ [kanban-releases](https://github.com/hburakdemir/kanban-releases)

## Güncelleme

Uygulama açılışta otomatik güncelleme kontrol eder. Yeni sürüm varsa üstte banner çıkar, tek tıkla güncellenir.