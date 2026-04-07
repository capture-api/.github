# Capture API

Capture API is a fast and developer-friendly REST API that allows you to capture screenshots of any public website. It is designed for developers who need reliable website previews, automated visual captures, and scalable screenshot generation.

---

## Features

* Capture full-page website screenshots
* High-resolution image output
* Mobile and desktop viewport support
* Fast and reliable API responses
* Secure API key authentication
* Simple REST API integration
* Scalable cloud infrastructure

---

## Use Cases

* Website preview thumbnails
* SEO monitoring and audits
* Visual regression testing
* Content archiving
* Competitor tracking
* Social media preview generation
* Automated reporting tools

---

## Example API Request

```bash
curl "https://api.captureapi.com/screenshot?url=https://example.com&apikey=YOUR_API_KEY"
```

---

## Example JSON Response

```json
{
  "success": true,
  "url": "https://example.com",
  "screenshot": "https://cdn.captureapi.com/screenshots/example.png"
}
```

---

## JavaScript Example

```javascript
fetch("https://api.captureapi.com/screenshot?url=https://example.com&apikey=YOUR_API_KEY")
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

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Submit a pull request

---

## License

MIT License

---

## Website

https://captureapi.com

---

## Support

If you find this project useful, please give it a star on GitHub.
