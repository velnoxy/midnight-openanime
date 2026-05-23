<div align="center">

```
███╗   ███╗██╗██████╗ ███╗   ██╗██╗ ██████╗ ██╗  ██╗████████╗
████╗ ████║██║██╔══██╗████╗  ██║██║██╔════╝ ██║  ██║╚══██╔══╝
██╔████╔██║██║██║  ██║██╔██╗ ██║██║██║  ███╗███████║   ██║   
██║╚██╔╝██║██║██║  ██║██║╚██╗██║██║██║   ██║██╔══██║   ██║   
██║ ╚═╝ ██║██║██████╔╝██║ ╚████║██║╚██████╔╝██║  ██║   ██║   
╚═╝     ╚═╝╚═╝╚═════╝ ╚═╝  ╚═══╝╚═╝ ╚═════╝ ╚═╝  ╚═╝   ╚═╝  
```

**A dark, minimal CSS theme for [OpenAnime](https://openani.me)**  
*inspired by [midnight-discord](https://github.com/refact0r/midnight-discord)*

![version](https://img.shields.io/badge/version-1.0-8db4f7?style=flat-square)
![platform](https://img.shields.io/badge/platform-OpenAnime-8db4f7?style=flat-square)
![license](https://img.shields.io/badge/license-MIT-6b9ef5?style=flat-square)

</div>

---

## Hakkında

**Midnight**, [refact0r](https://github.com/refact0r)'ın midnight-discord temasından ilham alınarak OpenAnime için sıfırdan yazılmış bir CSS temasıdır. Temel felsefesi sade, koyu ve dikkat dağıtmayan bir arayüz sunmak; animenin önüne geçmemek.

Catppuccin Mocha'nın mor aksanları yerine, gece mavisini (`#8db4f7`) ana renk olarak kullanır. Daha az gürültü, daha fazla içerik.

---

## Özellikler

- **Tam koyu tema** — `#111118` taban, `#0d0d14` derinlik rengi
- **Gece mavisi aksanlar** — mor yerine soğuk, serin bir mavi
- **Inter font** — piksel başına daha fazla netlik
- **Minimal cam efekti** — `backdrop-filter` ile hafif derinlik, abartısız
- **İnce scrollbar** — 6px, görünmez olmak üzere tasarlandı
- **Hafif ortam ışığı** — animasyonsuz, sakin arka plan parıltısı
- **Hem dark hem light mod** — light modda "Midnight Mist" paleti
- **Responsive** — mobil boyutlarda köşe yarıçapları otomatik küçülür

---

## Kurulum

OpenAnime'nin ayarlar sayfasına gidip özel CSS alanına aşağıdakini yapıştır:

```css
@import url('https://raw.githubusercontent.com/KULLANICI_ADIN/midnight-openanime/main/midnight.css');
```

> `KULLANICI_ADIN` yerine kendi GitHub kullanıcı adını yaz.

**Ya da** `midnight.css` dosyasının tamamını kopyalayıp doğrudan yapıştırabilirsin.

---

## Renk Paleti

| Renk | Hex | Kullanım |
|------|-----|---------|
| `--mn-bg0` | `#0d0d14` | En derin arka plan |
| `--mn-bg1` | `#111118` | Sayfa tabanı |
| `--mn-bg2` | `#16161f` | Paneller |
| `--mn-bg3` | `#1c1c27` | Kartlar |
| `--mn-bg4` | `#222233` | Hover / yükseltilmiş kartlar |
| `--mn-blue` | `#8db4f7` | Ana aksanı (mavi) |
| `--mn-ice` | `#b8d4ff` | Yumuşak vurgu |
| `--mn-white` | `#e8eaf2` | Birincil yazı |
| `--mn-sub1` | `#9da3bb` | İkincil yazı |
| `--mn-muted` | `#4a4f68` | Soluk yazı / ikonlar |

---

## Catppuccin Mocha ile Farkı

| | Midnight | Catppuccin Mocha |
|---|---|---|
| **Aksanı** | Gece mavisi `#8db4f7` | Mor `#cba6f7` |
| **Taban rengi** | `#111118` | `#1e1e2e` |
| **Font** | Inter | Junicode |
| **Animasyon** | Yok / minimal | Ortam float animasyonu |
| **Scrollbar** | 6px ince | 12px |
| **Felsefe** | Görünmez ol | Güzel ol |

---

## Özelleştirme

`:root` bloğundaki değişkenleri değiştirerek temayı kişiselleştirebilirsin:

```css
:root {
    /* Köşe yarıçapları — daha keskin için 0, daha yuvarlak için 16px */
    --radius-base: 10px;
    --radius-card: 12px;

    /* Geçiş hızları */
    --transition-fast: 0.15s;
    --transition-base: 0.2s;
}
```

Aksanı değiştirmek için `html.fds-theme-dark` bloğundaki şu satırları düzenle:

```css
--accent-primary:   #8db4f7;  /* ← istediğin renkle değiştir */
--accent-secondary: #b8d4ff;
--accent-tertiary:  #6b9ef5;
```

---

## Ekran Görüntüleri

> *yakında*

---

## Teşekkürler

- [refact0r](https://github.com/refact0r) — midnight-discord, bu temanın ilham kaynağı
- [catppuccin](https://github.com/catppuccin) — tema yapısı referansı
- [OpenAnime](https://openani.me) — platform

---

<div align="center">

*"Gece en iyi filtre."*

</div>
