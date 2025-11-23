# 🧑‍💻 SIMON DEV  
### Developer · Python · Automation · Multiplatform

🌐 **Website:** https://simondev.tech  
📧 **Email:** simon@simondev.tech  

---

## 🚀 About Me

I'm a developer focused on building practical tools that help people and small businesses:

- 🐍 Python automation & scripting  
- 🔍 Web scraping  
- 🌐 Small APIs (FastAPI)  
- 💻 Multiplatform dev (Python · Java · C# · Unity)  
- 🎨 Simple & clean web interfaces (HTML/CSS)

I like writing code that solves real problems.  
Focused on remote work, freelancing, and small real-world projects.

---

## 🧠 Dev Philosophy

- Keep it simple – small tools that do one thing well  
- Practical over perfect – shipped code beats “someday” code  
- Readable code – future-me should understand it fast  
- Automate boring stuff – if I repeat it, I script it  

---

## 💻 Example Snippet

\`\`\`python
import requests
from bs4 import BeautifulSoup

def get_price(url: str) -> float | None:
    """Simple example: extract price from a product page."""
    resp = requests.get(url, timeout=10)
    resp.raise_for_status()
    soup = BeautifulSoup(resp.text, "html.parser")

    price_el = soup.select_one(".price, .product-price, [data-price]")
    if not price_el:
        return None

    text = price_el.get_text(strip=True)
    digits = "".join(ch for ch in text if ch.isdigit() or ch == ".")
    return float(digits) if digits else None

if __name__ == "__main__":
    url = "https://example.com/perfume"
    price = get_price(url)
    print(f"Price: {price}€" if price is not None else "Price not found")
\`\`\`

---

## 🧰 Tech Stack

### 🐍 Core
- Python 3  
- FastAPI  
- Flask  
- BeautifulSoup4  
- Selenium  

### 💻 Development
- Java  
- C#  
- Unity  
- SQL  
- Git & GitHub  

### 🌐 Web
- HTML  
- CSS  
- JSON / XML  
- APIs  

---

## 📂 Featured Projects  
*(In progress — coming soon)*

### 🔍 Perfume Price Scraper  
Python scraper that extracts perfume prices from multiple stores.

### 🤖 Automation Bot  
Automates repetitive tasks: file organization, alerts, routines.

### 🌐 Perfume Recommendation API  
FastAPI backend recommending perfumes by notes & categories.

---

## 🖥️ dev@terminal

\`\`\`
simon@dev:~$ whoami
> developer · python · automation

simon@dev:~$ focus
> scraping, small tools, useful scripts

simon@dev:~$ portfolio
> https://simondev.tech
\`\`\`

---

## 📊 GitHub Stats

![Simon's GitHub stats](https://github-readme-stats.vercel.app/api?username=SimonDevv&show_icons=true&theme=tokyonight&hide_border=true)  
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=SimonDevv&layout=compact&theme=tokyonight&hide_border=true)

---

## 🛠️ What I'm Working On

- Improving Python automation & scraping  
- Building freelance-ready tools  
- Expanding my portfolio → https://simondev.tech  
- Designing simple, clean UI components  

---

## 📫 Contact

- 📧 Email: **simon@simondev.tech**  
- 🌐 Website: **https://simondev.tech**  
- 🐙 GitHub: **https://github.com/SimonDevv**  

---

⭐ **If you like my work, feel free to star my repositories!**
