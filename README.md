# Chenshuo Adhesive — Corporate Website (b2b-website)

Static, responsive, SEO-friendly marketing site for **Jiangxi Chenshuo Adhesive Industry Co., Ltd.** — one-stop supplier of insulating glass consumables.

Live domain: **https://www.chenshuo-ig.com**

## Files

```
b2b-website/
├── index.html        Home (EN) — company profile, product range, WhatsApp CTA
├── index-zh.html     Home (中文) — full Chinese version
├── index-ru.html     Home (РУС) — full Russian version
├── products.html     Full product line + technical specs
├── about.html        Company, manufacturing capabilities, quality, global reach
├── contact.html      Contact details + inquiry form
├── css/style.css     All styles (deep navy + amber, Barlow fonts)
└── images/           Real product & factory photos (27 files)
```

## Language switching

Every page is available in four languages: English, Chinese, Russian and Korean.
Each page header has a language switch (EN / 中文 / РУС / KO) linking to the same
page in the other languages:

- Home: index.html · index-zh.html · index-ru.html · index-ko.html
- Products: products.html · products-zh.html · products-ru.html · products-ko.html
- About: about.html · about-zh.html · about-ru.html · about-ko.html
- Contact: contact.html · contact-zh.html · contact-ru.html · contact-ko.html

Each language page links the others via `rel="alternate" hreflang` for SEO.
Upload all new files (index-zh/index-ru/index-ko and the -zh/-ru/-ko variants of
products/about/contact) to GitHub Pages when deploying.

## Contact information

- Contact: **Nicole Lee** (sales manager)
- WhatsApp / WeChat / Mobile: **+86 156 5127 0332**
- Email: **sales_chenshuo@163.com**
- Address: Gongye Wu Road, Yingtan Hi-tech Industrial Zone, Yingtan, Jiangxi, China
- Website: www.chenshuo-ig.com

WhatsApp link pattern used across the site: `https://wa.me/8615651270332?text=Hello%20Chenshuo%20team%2C%20I%20am%20interested%20in%20your%20insulating%20glass%20consumables.`

## Before going live (TODO)

1. **Formspree** — replace `https://formspree.io/f/YOUR_FORM_ID` in `contact.html` with your real Formspree form ID (create one at formspree.io).
2. **Verification** — after deploying, verify canonical URLs (`https://www.chenshuo-ig.com/...`) resolve correctly and Google Search Console is set up.

## Local preview

Open any `.html` file directly in a browser — no build step, no JavaScript required.
