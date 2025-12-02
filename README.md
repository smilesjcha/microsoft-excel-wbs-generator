# K-WBS Generator (Korean-Style Work Breakdown Structure Generator)

Automatically generate a Korean-style WBS schedule in Excel format.  
Supports Korean weekday formatting and timeline expansion based on task duration.

---

## ✨ Features
- Korean-style date & weekday format:  
  `MM-DD` + `(월,화,수,목,금,토,일)`
- Auto-generated timeline from min Start → max End date
- Fields included:
  - Version
  - WBS Code
  - Start / End Date
  - Person In Charge
  - Progress
  - Dependency
- Personal & educational use **FREE**
- Commercial use **requires a paid license**

---

## 📥 Install
```bash
# (Coming Soon)
pip install k-wbs
````

---

## 🚀 Usage Example

```python
from kwbs import generate_wbs_excel

generate_wbs_excel("wbs.xlsx", tasks)
```

See `/example` folder for full code and sample output.

---

## 💰 License & Pricing

| Use Case                                          | Status          | Price                 |
| ------------------------------------------------- | --------------- | --------------------- |
| Personal / Educational                            | Allowed         | Free                  |
| Commercial (Enterprise, SaaS, Gov, Paid Services) | ❌ Must purchase | **$5 / Organization** |

🔗 Purchase License:
➡ [https://gumroad.com/replace_with_purchase_link](https://gumroad.com/replace_with_purchase_link)

📧 Contact
[business.sjcha@gmail.com](mailto:business.sjcha@gmail.com)

---

## 🛠 Technology Stack

* Python 3.x
* xlsxwriter
* datetime

---

## 🧩 Roadmap

* PyPI Release
* GUI / Web version
* Auto-progress bar visualization
* Team collaboration mode

---

## ⭐ Support the Project!

If this project helps you, please give a star ⭐
and consider supporting development below 👇

[💙 Become a Sponsor](https://github.com/sponsors/replace_with_your_id)

---

© 2025 Cha Sungjae — All rights reserved.
