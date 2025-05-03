# 📊 Yelp Restaurant Analysis: User Engagement vs. Business Success

## 🧠 Problem Statement

In a competitive market like the restaurant industry, understanding what drives business success is vital. This project uses the **Yelp Open Dataset** to analyze how **user engagement metrics** (reviews, tips, check-ins) correlate with **restaurant success indicators** such as **ratings** and **review count**.

---

## 🎯 Research Objectives

1. **Correlation Analysis**: Quantify the relationship between user engagement (reviews, tips, check-ins) and business metrics (average star rating, total review count).
2. **Sentiment Impact**: Explore how positive sentiments in reviews and tips influence ratings and review count.
3. **Time-Based Trends**: Examine whether consistent engagement over time indicates long-term business success.

---

## 📐 Hypotheses

- Restaurants with more user engagement tend to have higher ratings and more reviews.
- Positive sentiment in user feedback leads to better average star ratings.
- Sustained engagement is a better predictor of business longevity than occasional bursts.

---

## 📚 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from datetime import datetime
import sqlite3
import folium
from geopy.geocoders import Nominatim
from matplotlib.colors import LinearSegmentedColormap
from IPython.display import display
import warnings
warnings.filterwarnings('ignore')
