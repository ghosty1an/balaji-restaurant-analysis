
# Анализ продаж и потребительского поведения фастфуд-ресторана "Balaji" 🍔🥤

### 📌 О проекте
Данный проект представляет собой комплексное исследование данных (EDA) и проверку статистических гипотез для оптимизации работы заведения быстрого питания. Цель анализа — не просто визуализировать данные, а найти конкретные точки роста выручки и способы оптимизации операционных процессов.

### 🛠 Стек технологий
- Python 
- Pandas
- NumPy
- Seaborn / Matplotlib 
- SciPy 

### 📊 Описание данных
В работе используется лог из 1000 транзакций, содержащий информацию о:
- Заказах: ID, дата, время суток, состав (блюдо, тип, цена, количество).
- Клиентах: Пол (Mr. / Mrs.), тип оплаты (Cash / Online).
- Финансах: Итоговая сумма чека и проверка скрытых комиссий.

### 🎯 Ключевые бизнес-вопросы
1. Платежное поведение: Как тип оплаты влияет на средний чек и нагрузку на кассу? 
2. Демография: Есть ли статистически значимая разница в тратах мужчин и женщин? 
3. Эффективность меню: Какие позиции приносят основной доход и что предложить клиентам дополнительно (Cross-sell)? 
4. Тайм-менеджмент: В какие часы и дни ресторан наиболее загружен и как оптимизировать график персонала?

### 📈 Основные инсайты и рекомендации (Executive Summary)
1. Оптимизация платежей:

- Инсайт: Доля наличных платежей крайне высока, что замедляет обслуживание и несет риски инкассации.

- Рекомендация: Внедрить скидку 2% при оплате онлайн или через приложение для увеличения пропускной способности.

2. Гендерные различия:

- Инсайт: Тест Манна-Уитни подтвердил различия в структуре потребления: мужчины предпочитают сытные комбо-наборы, женщины — премиальные напитки.

- Рекомендация: Настроить Cross-sell предложения — предлагать легкие закуски к дорогим напиткам для женской аудитории.

3. Режим работы:

- Инсайт: Нетипичный для фастфуда спад в выходные дни указывает на локацию в бизнес-центре или кампусе.

- Рекомендация: Оптимизировать ФОТ (фонд оплаты труда), сократив количество персонала в выходные, или запустить акции "Семейный выходной" для привлечения местных жителей.

### 🚀 Как запустить проект
1. Клонируйте репозиторий:

    git clone https://github.com/your-username/balaji-analysis.git

2. Установите необходимые библиотеки:

    pip install pandas seaborn scipy matplotlib

# In English

# Sales and Consumer Behavior Analysis: "Balaji" Fast Food Restaurant 🍔🥤
### 📌 Project Overview

This project is a comprehensive Exploratory Data Analysis (EDA) and statistical hypothesis testing aimed at optimizing operations for the "Balaji" fast food establishment. The goal is to move beyond simple data visualization to identify specific revenue growth opportunities and operational efficiencies.

### 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- SciPy

### 📊 Dataset Description

The analysis is based on a log of 1,000 transactions, containing detailed information on:

- Orders: Unique IDs, dates, time of day, and item details (name, category, price, and quantity).
- Customers: Gender (Mr. / Mrs.) and payment method (Cash / Online).
- Finance: Total transaction amounts and verification of hidden commissions.

### 🎯 Key Business Questions
- Payment Behavior: How does the payment method impact the average order value (AOV) and checkout speed? 
- Demographics: Is there a statistically significant difference in spending patterns between male and female customers? 
- Menu Efficiency: Which items drive the most revenue, and what are the best opportunities for cross-selling? 
- Time Management: When are the peak hours/days, and how can staff scheduling be optimized? 

### 📈 Key Insights & Recommendations:
1. Payment Optimization:
- Insight: The high volume of cash payments slows down service and increases cash-handling risks.
- Recommendation: Introduce a small incentive (e.g., a 2% discount) for online or app-based payments to increase throughput and reduce cash reliance.

2. Demographic Analysis:
- Insight: The Mann-Whitney U test confirmed distinct consumption patterns: men prefer hearty "Combo" meals, while women favor premium beverages.
- Recommendation: Implement targeted cross-sell strategies—for instance, offering light snacks or appetizers to female customers purchasing premium drinks.

3. Operational Timing
- Insight: An unusual drop in demand during weekends suggests the location is likely in a business district or student campus.
- Recommendation: Optimize labor costs by reducing staff shifts on weekends or launching "Family Weekend" promotions to attract local residents.

### 🚀 Getting Started

1. Clone the repository:

    git clone https://github.com/your-username/balaji-analysis.git

2. Install dependencies:

    pip install pandas seaborn scipy matplotlib