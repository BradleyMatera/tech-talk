# 🛍️ Tech-Talk Web Store — Project TODO

## 🎯 Project Goal

Launch polished, reusable web store templates quickly, and use AI to accelerate development by:
- Debugging and configuring efficiently using terminal commands
- Maintaining separation of concerns between data, logic, and UI
- Applying security best practices for real public-facing apps
- Optimizing speed (load time + dev time)
- Delivering clean, consistent UI/UX with real branding and style
- Avoid rebuilding frontend from scratch by launching prebuilt templates with minimal design overhead

## ✅ PHASE 1: Core Setup

- [x] Create Firebase project (techtalk-7ea90)
- [x] Enable Firestore and Realtime DB
- [x] Setup public rules for dev (read/write)
- [x] Connect Firebase to Glitch IDE
- [x] Sync project to GitHub (BradleyMatera/tech-talk)
- [ ] Add live deploy preview (Firebase Hosting or Glitch)

---

## 🖼️ PHASE 2: Frontend Layout

> Note: Since this project is template-first, the goal is not to build custom UI from scratch, but to adapt and wire existing frontend templates to live Firebase data.

- [ ] Build basic home page (header, footer, grid layout)
- [ ] Create product card template (image, title, price, "Add to cart")
- [ ] Build navigation bar (Home, Cart, Checkout)
- [ ] Add loading state / error handling for products
- [ ] Load product data from Firestore

---

## 🛒 PHASE 3: Cart Functionality

- [ ] Create Cart component/page
- [ ] Add "Add to Cart" button on each product
- [ ] Store cart in Realtime DB or localStorage
- [ ] Display cart contents with quantity and total
- [ ] Implement "Remove from cart" and "Clear cart"

---

## 🔐 PHASE 4: Auth Integration

- [ ] Enable Firebase Authentication (Google Sign-In)
- [ ] Add "Login with Google" button
- [ ] Restrict cart/checkout to logged-in users
- [ ] Display user name/avatar when signed in

---

## 💸 PHASE 5: Checkout & Orders

- [ ] Build simple checkout form (name, shipping, etc.)
- [ ] Save orders to Firestore under user ID
- [ ] Add "Your Orders" page (user sees history)
- [ ] Show confirmation message / order ID

---

## ✨ PHASE 6: Admin Panel (Optional)

- [ ] Create `/admin` route
- [ ] Add products manually from UI
- [ ] Secure with `isAdmin` flag in user Firestore doc
- [ ] Upload product images (Firebase Storage)

---

## 🚀 PHASE 7: Launch & Polish

- [ ] Deploy to Firebase Hosting or custom domain
- [ ] Add favicon, meta tags, Open Graph
- [ ] Add basic analytics (Firebase or Plausible)
- [ ] Write README with deploy steps
- [ ] Add license and terms (basic placeholder)

---

## ✅ Current Sprint Priorities

- [ ] Build and style the first real product card (Squirtle T-shirt, with image, price, and description)
- [ ] Create `/products` collection in Firestore with 3 initial entries
- [ ] Write JS fetch logic to load and display products dynamically on the homepage
- [ ] Build GitHub Action or Glitch script to auto-deploy latest changes
- [ ] Add project-wide `.env` loader to connect Firebase config to both frontend and backend
- [ ] Ensure cart state syncs across tabs (use Realtime DB or localStorage for now)
- [ ] Test product listing on multiple screen sizes (mobile, tablet, desktop)
- [ ] Create and commit `.env.example` file for environment variables
- [ ] Create README section for how to run the project locally
- [ ] Assign shared team roles for Firebase project (auth, database, functions, studio)
- [ ] Connect and verify live Firestore read/write in both local and Glitch environments
- [ ] Verify GitHub repo has all project files (check .firebaserc, database.rules.json, firestore.rules, etc.)
