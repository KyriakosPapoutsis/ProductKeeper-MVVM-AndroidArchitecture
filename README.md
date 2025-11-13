# ProductsListApplication - Android App 

This Android application showcases a complete product catalog system with Firebase integration, user authentication, product browsing, reviews, wishlists, and purchase management.

Developed by **Kyriakos Papoutsis**

Bachelor of Science (BSc) in Digital Systems
*Specialization: Software and Data Systems*  
*Secondary Track: Information Systems*  
Department of Digital Systems, University of Piraeus

---

## 📱 Features

### 🔐 User Authentication
- Register and log in using Firebase Authentication
- Email-based login system

### 🛍 Product Catalog
- Browse a collection of products with:
  - Name, description, price, discount, image
  - Specifications (size, color, material, etc.)
- Filter by:
  - Brand  
  - Price range  
  - Type  
- Search products by name
- Navigation handled via Android Jetpack Navigation Component

### ⭐ Wishlist
- Add/remove products from a personal wishlist
- Wishlist items stored in Firebase Firestore

### 🧾 Purchases
- Submit purchase quantities using a Material Slider
- Update purchase quantities directly from the list
- Purchases stored in Firestore

### 📝 Reviews
- Leave reviews only for previously purchased products
- 5-star rating bar and text review input
- View all reviews associated with a product

### 👤 User Profile
- Display logged-in user’s email
- Logout functionality with session clearing

---

## 🏗 Architecture & Tech Stack

| Layer                | Technologies                                                             |
| -------------------- | ------------------------------------------------------------------------ |
| **Language**         | Kotlin                                                                   |
| **IDE**              | Android Studio                                                           |
| **Architecture**     | MVVM (ViewModel, LiveData)                                               |
| **Backend Services** | Firebase Authentication • Firebase Firestore                             |
| **UI Components**    | RecyclerView (Products, Purchases, Reviews) • Material Design Components |
| **Navigation**       | Jetpack Navigation Component                                             |
| **Async Operations** | Kotlin Coroutines                                                        |
| **Image Loading**    | Glide                                                                    |
| **Build System**     | Gradle                                                                   |

---

## 🖼 Screenshots

```markdown
### 📸 Home Screen
![Home](screenshots/home.png)

### 🛍 Product Catalog
![Catalog](screenshots/catalog.png)

### ⭐ Reviews
![Reviews](screenshots/reviews.png)



