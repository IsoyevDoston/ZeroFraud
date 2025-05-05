# ZeroFraud
💳 Tranzaksiyalardagi Anomaliyalarni Aniqlash (Anomaly Detection)

📌 Loyihaning Maqsadi
Tranzaksiyalardagi anomaliyalarni aniqlash – bu odatiy tranzaksiya modelaridan keskin farq qiluvchi holatlarni topish bo‘lib, ular ko‘pincha firibgarlik yoki g‘ayrioddiy xatti-harakatlarni anglatadi. Bu, ayniqsa, moliyaviy sohada firibgarliklarni aniqlash va foydalanuvchi hisoblarini himoya qilish uchun kerak.

🔍 Asosiy Foydalanish Holati: Firibgarlikni Aniqlash
Model odatiy xarid miqdori, tezligi va joylashuvi kabi foydalanuvchining xarid qilish odatlarini o‘rganadi. Agar tranzaksiya bu modelaridan keskin farq qilsa (masalan, katta xarid yoki notanish joydan tranzaksiya) – model buni anomaliya deb belgilaydi va zarur choralar ko‘riladi.

🗂 Ma’lumotlar Haqida
Foydalanilgan fayl: transaction_anomalies_dataset.csv

Asosiy ustunlar:

Transaction_ID, Transaction_Amount, Transaction_Volume

Average_Transaction_Amount, Frequency_of_Transactions, Time_Since_Last_Transaction

Day_of_Week, Time_of_Day

Age, Gender, Income, Account_Type

🤖 Ishlatilgan Model
Model: IsolationForest

Notbuk: anomaly_detection.ipynb

Kutubxonalar: pandas, matplotlib, seaborn, scikit-learn

📊 Baholash Natijalari
Precision: Normal: 1.00 | Anomaliya: 1.00

Recall: Normal: 1.00 | Anomaliya: 1.00

Accuracy: 1.00

⚙️ O‘rnatish Ko‘rsatmalari
Git orqali klonlash:
git clone https://github.com/IsoyevDoston/ZeroFraud/Anomaly-Detection-in-Transactions.git

Virtual muhit yaratish va faollashtirish:
python -m venv venv  
source venv/bin/activate
 
Kutubxonalarni o‘rnatish:
pip install pandas matplotlib seaborn scikit-learn

anomaly_detection.ipynb faylini oching va barcha faylarni ishga tushiring
Yoki Google Colab’da .csv fayllarni yuklab olib, notbukni ishga tushiring.

📬 Bog‘lanish
LinkedIn: Doston Isoyev

Email: isoyevdoston1@gmail.com or rustamxonimamov@gmail.com

Telegram: @pacckard or @rustamftw
