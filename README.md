# Moodly
## Emotion Diary App

[Google Drive Link](https://drive.google.com/drive/folders/1PeCQRZHk_ZaY5yLNeHrM8BhwLSDH5nWr?usp=sharing)

---

## 📌 Background & Motivation
- Record and save emotions
- Explore others' emotions
- Chat with a chatbot
- Visualize my emotions on a map

---

## 👥 Roles
| Name  | Role |
|-------|------------------------------------------------|
| Kim Hyuk  | Backend, DB, Rest API, Chatbot, Retrofit |
| Jang Seokmin | Home Fragment, Feed Fragment, Navigation, UI/UX |
| Yeom Jungwoo | Express Fragment, Popup, Supporting Functions |

---

## 🏗 Architecture
![Architecture](https://velog.velcdn.com/images/jg31109/post/85f1c32f-500b-423f-83c3-c9926b709767/image.png)

---

## 🗃 ERD (Entity Relationship Diagram)
![ERD](https://velog.velcdn.com/images/jg31109/post/925faa5f-8149-45bf-96af-568eae86ad1f/image.png)

---

## 📱 Android
- Communicates with the Django server via Retrofit using REST API format
- Developed using Kotlin
- Implements social login via Firebase
- After Firebase authentication, a request is sent to the Django server, which issues a JWT token for the user

---

## 💻 Backend
- Developed using Django REST Framework (DRF)
- Communicates with Android via REST API
- Uses MySQL as the database
- Deployed on the cloud, enabling external access

---

## 🏠 RoomDB
- Uses RoomDB for efficient storage of user diary data
- Local data storage improves dashboard access speed
- JWT tokens for login and security are managed via SharedPreferences

---

## 🔗 Used APIs
- **Map Function**: Google Maps API
- **Chatbot Function**: ChatGPT 3.5-turbo model

---

## ⏳ ETL Scheduling
- Data is extracted using Interpark page crawling and YouTube v3 API
- Updated daily at **00:00 AM** using Apache Airflow
- **Interpark Crawling** → Used for book recommendations
- **YouTube v3 API** → Used for music playlist recommendations
- Since book rankings and YouTube algorithms change daily, Apache Airflow is used for scheduled updates

---

## 🔗 REST API Endpoints
![REST API](https://velog.velcdn.com/images/jg31109/post/899266b8-0236-47b7-af09-fd55a7a3b4ee/image.png)

---

## 🎨 Application UI
Some UI examples are provided below. More images can be found in the link.
[View UI Design](https://www.canva.com/design/DAGZHUK5Do8/gtTiU-ScQX0FyG48jqteTQ/edit?utm_content=DAGZHUK5Do8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
