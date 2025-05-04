# AdvancedWebViewApp-FullSource


📘 README.md – Advanced WebView App
markdown
Copy
Edit
# 🌐 Advanced WebView App – Android

A powerful Android WebView application built with **Jetpack Compose**, **modular architecture**, and advanced features like pull-to-refresh, file upload/download, shimmer loading, deep linking, and Firebase integration. Includes CI/CD support with GitHub Actions and Cucumber BDD testing.

---

## 🚀 Features

✅ Modular Architecture (`core`, `navigation`, `feature-webview`)  
✅ Single-Activity Jetpack Compose App  
✅ Bottom Navigation: News, TV, Radio, e-Paper, Contact  
✅ Full WebView Support:
- Back/Forward/Refresh
- Pull to Refresh
- File Upload / Download
- JavaScript Injection  
✅ Shimmer Loading  
✅ Deep Link Support  
✅ Firebase Integration:
- Auth
- Firestore
- Crashlytics
- Remote Config (Dynamic URLs)  
✅ Environment-Based URL Management with `.env`  
✅ Build Variants: `dev`, `prod`  
✅ Unit Testing + Cucumber BDD  
✅ GitHub Actions CI/CD  
✅ Dark / Light Theme Support  

---

## 🛠️ Tech Stack

- Kotlin + Jetpack Compose  
- Modular MVVM Architecture  
- Firebase Suite  
- Kotlinx Serialization  
- Hilt Dependency Injection  
- Retrofit + OkHttp  
- Cucumber + JUnit 5  
- GitHub Actions CI/CD  
- Gradle Kotlin DSL  

---

## 📦 Project Structure

📁 app
📁 core
📁 feature-webview
📁 navigation
📁 shared
├── build.gradle.kts
├── settings.gradle.kts

yaml
Copy
Edit

---

## 🔧 Local Setup

### 1. Clone the Repository

```bash
git clone https://github.com/androidtutorialonline/AdvancedWebViewApp-FullSource.git
cd AdvancedWebViewApp-FullSource
2. Firebase Setup
Add your google-services.json to app/

Enable Auth, Firestore, Remote Config

3. Setup Environment Variables
bash
Copy
Edit
cp .env.example .env
Edit .env to set:

env
Copy
Edit
URL_NEWS=https://your-news-url.com
URL_TV=https://your-tv-url.com
...
4. Run the App
bash
Copy
Edit
./gradlew assembleDevDebug
./gradlew installDevDebug
🧪 Testing
Run unit & BDD tests:

bash
Copy
Edit
./gradlew test
./gradlew connectedAndroidTest
🤖 CI/CD
GitHub Actions will run on push:

Lint checks (ktlint, detekt)

Unit tests

Build verification

See .github/workflows/android.yml

📄 License
MIT License - LICENSE

✨ Credits
Maintained by androidtutorialonline

yaml
Copy
Edit

---

Would you like me to:

- Commit and push this `README.md` to the GitHub repo?
- Or include it in a `.zip` download?

Let me know how you'd like to proceed.
