# Management System - Front-end Task 2

A modern, responsive front-end web application featuring a landing page with hero slider, authentication system, and interactive dashboard with course modals.

## 🚀 Live / File Structure

- `index.html`: Landing page with dynamic carousel slider, goal description section, and navigation dropdown.
- `login.html`: Sign-in page with credential validation and feedback toasts.
- `register.html`: Sign-up registration page.
- `home.html`: Authenticated dashboard featuring course cards and modal detail popups.
- `hero_slide1.jpg`, `hero_slide2.jpg`, `hero_slide3.jpg`: Carousel banners.
- `goal_section_img.jpg`: Goal section banner image.

---

## 🔑 Demo Account Credentials

Use the following fixed credentials on `login.html`:

| Field | Value |
|---|---|
| **Email** | `hana@gmail.com` |
| **Password** | `123456789` |

---

## 🧭 Page Flow

1. **`index.html`** → Click **Login Now** or navbar dropdown **Login** → Redirects to `login.html`
2. **`login.html`** → Enter credentials (`hana@gmail.com` / `123456789`) → Shows success toast and redirects to `home.html`
3. **`home.html`** → Click **Learn More** on any course (HTML, CSS, Bootstrap, JavaScript) → Opens detail modal popup
4. **`home.html`** → Click **Logout** in navbar dropdown → Returns to `login.html`

---

## 🛠️ Features

- **Responsive Design**: Clean UI supporting desktop and mobile devices.
- **Interactive Modals**: Course cards open dialogs with details, closeable via buttons, backdrop click, or `Escape` key.
- **Carousel Slider**: Automatic and manual transitions with indicator dots and prev/next buttons.
- **Accessible Navbars**: Click-to-toggle dropdown menus with outside-click dismissal.
