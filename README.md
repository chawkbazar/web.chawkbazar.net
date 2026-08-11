# KhaboKothay — আজ কোথায় খাবো?

KhaboKothay is a mobile-first restaurant discovery and deals application for Bangladesh. Browse dining options, explore authentic menus, read verified reviews, find active discount deals, and save favorite spots in Dhanmondi, Gulshan, Banani, Uttara, Mirpur, and across Dhaka.

---

## 🚀 Quick Start (Local Development)

```bash
# 1. Install dependencies
npm install

# 2. Start dev server
npm run dev
```

App runs locally at `http://localhost:3000`.

---

## 🔒 Firebase Setup & Rule Deployment

This application uses the Firebase Project `khabokothay`.

### 1. Enable Authentication Providers
Before signing in, enable authentication in the **Firebase Console**:
1. Go to **Firebase Console** -> **Authentication** -> **Sign-in method**.
2. Enable **Email/Password**.
3. Enable **Google Sign-In** (add support email if prompted).

### 2. Deploy Firestore Rules & Indexes
Use the Firebase CLI to deploy rules and index configurations:

```bash
# Login to Firebase
firebase login

# Set active project
firebase use khabokothay

# Deploy Firestore Security Rules & Indexes
firebase deploy --only firestore

# Deploy Storage Security Rules
firebase deploy --only storage
```

---

## 🛠️ Contact & Support

- **Support Email**: khabokothay@gmail.com
- **Hotline**: 01948879984
- **Language**: English & Bangla (বাংলা)
