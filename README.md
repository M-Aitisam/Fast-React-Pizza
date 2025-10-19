# 🍕 Fast React Pizza Co.

### 🚀 [Live Demo → Fast React Pizza Co.](https://fast-pizzaco.netlify.app/)

A simple, modern, and user-friendly pizza ordering web app built with **React**, **Redux Toolkit**, and **Tailwind CSS**.

---

## 📝 Description

**Fast React Pizza Co.** is a responsive pizza ordering application that allows users to browse pizzas, add them to a cart, and place an order — all without needing an account.  
Built using the latest React technologies, it demonstrates concepts like **global state management**, **routing**, and **API integration** in a clean and minimal design.

---

## ⚙️ How It Works

1. Users place an order by submitting their details (name, phone number, address, and selected pizzas).  
2. The order is sent as a **POST request** to the API.  
3. The API returns a **unique order ID**, which is displayed to the user for future tracking.  
4. Orders can later be retrieved or updated (e.g., marked as “priority”).

---

## ✨ Features

✅ **No Account Required**  
Just enter your name to start ordering — no login or password needed.

✅ **Dynamic Menu**  
The pizza menu is fetched live from an API, so you always see the most updated options.

✅ **Easy Ordering**  
Add multiple pizzas, enter your info, and order in one step.

✅ **Priority Orders**  
Need your pizza fast? Mark your order as “priority” (20% extra) for quick delivery.

✅ **Post-Order Modifications**  
Changed your mind? You can still mark your order as “priority” after placing it.

✅ **Payment on Delivery**  
No credit cards needed — pay when your pizza arrives.

✅ **Unique Order ID**  
Every order gets a unique ID for easy lookup later.

---

## 📄 Pages

| Page | Path | Description |
|------|------|-------------|
| 🏠 **Homepage** | `/` | Overview of the app |
| 🍕 **Pizza Menu** | `/menu` | Browse available pizzas |
| 🛒 **Cart** | `/cart` | View and modify selected pizzas |
| 🧾 **Place Order** | `/order/new` | Enter your info and place an order |
| 🔍 **Order Lookup** | `/order/:orderID` | Check your order by ID |

---

## 🧠 State Management

| State | Type | Description |
|--------|------|-------------|
| 👤 **User** | Global UI State | Stores username and user input |
| 🍕 **Menu** | Remote State | Fetched from API |
| 🛍 **Cart** | Global UI State | Stores pizzas added to cart |
| 📦 **Order** | Remote State | Sent and fetched from API |

---

## 🛠️ Technologies Used

- ⚛️ **React** – Component-based UI
- 🧭 **React Router** – Routing and navigation
- 🧰 **Redux Toolkit** – State management
- 🎨 **Tailwind CSS** – Styling and responsive design
- 🌐 **Netlify** – Deployment and hosting
- 📡 **Fake API / JSON Server** – Backend simulation

---

## 🌍 Live Preview

👉 **Visit here:** [https://fast-pizzaco.netlify.app/](https://fast-pizzaco.netlify.app/)

---

## 🧑‍💻 Author

**Muhammad Aitisam Ahmed**  
📧 [GitHub Profile](https://github.com/M-Aitisam)  
🌐 [Live Project Link](https://fast-pizzaco.netlify.app/)

---

## 📸 Screenshots (Optional)

You can add images like this once you have screenshots:

```markdown
<img width="1910" height="802" alt="image" src="https://github.com/user-attachments/assets/5890160b-d62a-447b-b23f-4ef9cff6ad86" />

<img width="1918" height="784" alt="image" src="https://github.com/user-attachments/assets/148ca7f3-bb94-4324-ba1e-c36edb07c151" />

<img width="1918" height="608" alt="image" src="https://github.com/user-attachments/assets/13c81715-5370-44fb-8175-8f46b5b6cb5a" />

<img width="1917" height="771" alt="image" src="https://github.com/user-attachments/assets/cf477c2d-631e-4c97-9a8d-9035b475bf96" />
