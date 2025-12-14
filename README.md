# 🌍 Countries JSON Dataset

![JSON](https://img.shields.io/badge/Format-JSON-blue)
![Countries](https://img.shields.io/badge/Countries-240%2B-green)
![Open Source](https://img.shields.io/badge/Open%20Source-Yes-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Repo Size](https://img.shields.io/github/repo-size/ameerzain/countries)

A clean, lightweight, and developer-friendly JSON dataset containing a comprehensive list of countries and territories with their standardized country codes.

This repository is designed to be **simple**, **reusable**, and **framework-agnostic**, making it ideal for applications that need country selection, geolocation, internationalization, or global configuration support.

---

## 📦 Contents

- `countries.json` – A JSON array of country objects with:
  - `name` – Official or commonly used country/territory name
  - `code` – ISO 3166-1 alpha-2 country code

### Example
```json
{
  "name": "India",
  "code": "IN"
}
```

---

## ✨ Features

- ✅ 240+ countries & territories
- ✅ ISO 3166-1 alpha-2 country codes
- ✅ Clean and consistent JSON structure
- ✅ Ready for frontend & backend usage
- ✅ Perfect for dropdowns, filters, and forms
- ✅ Easy to extend and maintain

---

## 🚀 Use Cases

- 🌍 Country selector dropdowns
- 📦 Address & shipping forms
- 🌐 Internationalization (i18n)
- 📊 Analytics & reporting
- 📱 Mobile and web applications
- 🔌 API integrations
- 🧩 Configuration files

---

## 🌐 Public API / Raw JSON Access

### 🔗 Raw JSON URL
```
https://raw.githubusercontent.com/ameerzain/countries/main/countries.json
```

---

## 📌 Usage Examples

### JavaScript (Fetch API)
```js
fetch('https://raw.githubusercontent.com/ameerzain/countries/main/countries.json')
  .then(response => response.json())
  .then(data => console.log(data));
```

### Python
```python
import requests

url = "https://raw.githubusercontent.com/ameerzain/countries/main/countries.json"
countries = requests.get(url).json()

print(countries)
```

### HTML (Dropdown Example)
```html
<select>
  <option value="IN">India</option>
  <option value="US">United States</option>
  <option value="GB">United Kingdom</option>
</select>
```

> ℹ️ **Note:**  
> This dataset is served via GitHub Raw and is suitable for light to medium usage.  
> For high-traffic production environments, consider caching or self-hosting the file.

---

## 📊 Data Format

```json
[
  {
    "name": "India",
    "code": "IN"
  },
  {
    "name": "United States",
    "code": "US"
  }
]
```

---

## 🤝 Contributing

Contributions are welcome!

- Add missing countries or territories
- Improve naming consistency
- Update deprecated country codes
- Add additional metadata (flags, calling codes, regions)

---

## 📄 License

This project is open-source and available under the **MIT License**.

---

## 👤 Author

**Ameer Zain**  
GitHub: https://github.com/ameerzain

If you find this repository useful, consider giving it a ⭐ to support the project.

---

Happy coding! 🚀
