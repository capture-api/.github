<p align="center">
  <img src="https://captureapi.net/captureapi-icon.png" width="120" alt="Capture API Logo">
</p>

<h1 align="center">Capture API</h1>

<p align="center">
Fast API for capturing website screenshots and webpage previews.
</p>

<p align="center">

![API](https://img.shields.io/badge/API-CaptureAPI-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-REST-orange)
![GitHub Org](https://img.shields.io/badge/GitHub-capture--api-black)

</p>

<p align="center">
<a href="https://captureapi.net">🌐 Website</a> •
<a href="https://captureapi.net/docs">📚 Docs</a> •
<a href="https://api.captureapi.net">⚡ API</a>
</p>

---

## 🚀 Chrome Extension

<p align="center">

<a href="https://chromewebstore.google.com/detail/full-page-screenshot-scre/ppgnmecncgafcagagjbidcofpnooepin">

![Chrome Web Store](https://img.shields.io/badge/Chrome%20Extension-Install-blue?logo=googlechrome)
![Chrome Web Store Users](https://img.shields.io/chrome-web-store/users/ppgnmecncgafcagagjbidcofpnooepin)
![Chrome Web Store Rating](https://img.shields.io/chrome-web-store/rating/ppgnmecncgafcagagjbidcofpnooepin)

</a>

</p>

Full Page Screenshot Chrome Extension built by **Capture API**.

✔ Capture entire webpage  
✔ Export screenshots instantly  
✔ Fast and lightweight  
✔ Works on any website  

Install from Chrome Web Store:

https://chromewebstore.google.com/detail/full-page-screenshot-scre/ppgnmecncgafcagagjbidcofpnooepin

---

# ⚡ Use Cases

- Website preview thumbnails
- SEO monitoring and audits
- Visual regression testing
- Content archiving
- Competitor tracking
- Social media preview generation
- Automated reporting tools

---

## Example API Request

```bash
curl "https://api.captureapi.net/screenshot?url=https://example.com&apikey=YOUR_API_KEY"
```

---

## Example JSON Response

```json
{
  "success": true,
  "url": "https://example.com",
  "screenshot": "https://cdn.captureapi.net/screenshots/example.png"
}
```

---

## JavaScript Example

```javascript
fetch("https://api.captureapi.net/screenshot?url=https://example.com&apikey=YOUR_API_KEY")
  .then(response => response.json())
  .then(data => console.log(data));
```

---

## Authentication

All API requests require an API key.

Add your API key to each request:

```
apikey=YOUR_API_KEY
```

---

## Roadmap

* PDF capture support
* Video capture API
* Scheduled screenshot capture
* Webhook notifications
* SDKs for multiple programming languages

---

## Website

https://captureapi.net

---

## Support

If you find this project useful, please give it a star on GitHub.
