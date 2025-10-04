# 🌍 O‘zbekiston ekologik muammolari statistik tahlili

## 📘 Loyihaning maqsadi
Ushbu loyiha doirasida **O‘zbekistondagi asosiy ekologik muammolar** — xususan:
- 🌊 Aral dengizining qurishi va maydonining kamayishi,  
- 🗑️ Chiqindilar miqdorining ortishi,  
- ♻️ Atmosfera ifloslanish darajasi,  
- 🌱 Ekotizimga ta’sir qiluvchi omillar  

statistik ma’lumotlar asosida tahlil qilinadi.  
Tahlil **Python (Pandas, Matplotlib, Seaborn, NumPy)** kutubxonalari yordamida amalga oshirilgan.

---

## 📊 Manbalar
- [O‘zbekiston Respublikasi Ekologiya, atrof-muhitni muhofaza qilish va iqlim o‘zgarishi vazirligi](https://eco.gov.uz/)
- [UNEP – United Nations Environment Programme](https://www.unep.org/)
- Mahalliy kuzatuvlar va xalqaro ochiq ma’lumotlar (CSV, Excel, JSON formatlarda)

---

## ⚙️ Loyiha bosqichlari

### 1️⃣ Kutubxonalarni ulash
```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
import xml.etree.ElementTree as ET
import json
from google.colab import files
