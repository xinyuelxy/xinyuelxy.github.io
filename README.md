# Xinyue Li Personal Website

Static academic homepage for `xinyuelixy.com`, styled after `luost26/academic-homepage` layout 2.

## Local Files

- `index.html`: homepage.
- `publications/index.html`: publication list grouped by year.
- `experiences/index.html`: experiences and service timeline.
- `awards/index.html`: awards.
- `styles.css`: shared styles.
- `assets/profile.jpg`: portrait.
- `image/Peking_University_seal.svg.png`: Peking University badge.
- `image/SWU.png`: Southwest University badge.
- `CNAME`: custom domain for GitHub Pages.
- `cv__ENGLISH_.pdf`: linked Curriculum Vitae.
- `pub/`: linked publication PDFs.

## Deploy to GitHub Pages

1. Create a public GitHub repository named `xinyuelxy.github.io`.
2. Upload these files to the repository root.
3. Open `Settings` -> `Pages`.
4. Set `Source` to `Deploy from a branch`.
5. Set `Branch` to `main` and folder to `/root`, then save.
6. In `Custom domain`, enter `xinyuelixy.com`.
7. After DNS verification passes, enable `Enforce HTTPS`.

## Aliyun DNS

Add these records for `xinyuelixy.com`:

| Type | Host | Value |
| --- | --- | --- |
| CNAME | `www` | `xinyuelxy.github.io` |
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |

Keep `CNAME` in the repository root with exactly:

```txt
xinyuelixy.com
```
