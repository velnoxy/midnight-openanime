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

![version](https://img.shields.io/badge/version-1.3-8db4f7?style=flat-square)
![platform](https://img.shields.io/badge/platform-OpenAnime-8db4f7?style=flat-square)
![license](https://img.shields.io/badge/license-MIT-6b9ef5?style=flat-square)

</div>

---

## Hakkında

**Midnight**, [refact0r](https://github.com/refact0r)'ın midnight-discord temasından ilham alınarak OpenAnime için sıfırdan yazılmış bir CSS temasıdır. Temel felsefesi sade, koyu ve dikkat dağıtmayan bir arayüz sunmak; animenin önüne geçmemek.

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


Releases kıdmındaki en son güncellenmiş `midnight.css` dosyasının indirip bu şekilde kurulumunu yapabilirsin.

<img width="720" height="405" alt="ezgif-75a7a77c20c4bbc1" src="https://github.com/user-attachments/assets/dfd6b33f-33ed-4bd4-9590-7dec330722e8" />


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

<img width="1919" height="995" alt="image" src="https://github.com/user-attachments/assets/b1a5db82-bcc8-4f61-8508-04470d3d9025" />
<img width="1919" height="1000" alt="image" src="https://github.com/user-attachments/assets/cd71d31d-9155-4a04-bba1-e906e5a5ec0e" />
<img width="1919" height="998" alt="image" src="https://github.com/user-attachments/assets/0dad0565-320e-43a5-ba76-bf11ce95b4a3" />
<img width="1919" height="996" alt="image" src="https://github.com/user-attachments/assets/3c296597-39d2-4d8d-8774-e9c6acc1af1b" />
<img width="1919" height="993" alt="image" src="https://github.com/user-attachments/assets/a4ba8cc9-3926-4917-8b65-b835446ef335" />
<img width="1919" height="1000" alt="image" src="https://github.com/user-attachments/assets/7ad8fdc7-5bd6-4744-a737-0fa9058a2cad" />
<img width="1919" height="1000" alt="image" src="https://github.com/user-attachments/assets/fb72e54f-7b79-498f-87f8-5fa96497cc9b" />


---

## Teşekkürler

- [refact0r](https://github.com/refact0r) — midnight-discord, bu temanın ilham kaynağı
- [OpenAnime](https://openani.me) — platform

---

<div align="center">

*"Gece en iyi filtre."*

</div>
