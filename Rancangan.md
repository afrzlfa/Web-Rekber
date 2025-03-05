Siap, nih langsung list **endpoint lengkapnya** buat sistem **rekber 4 role (Buyer, Seller, Rekber, Admin)** yang pakai Google OAuth, Buyer bisa pilih Rekber:

---

# 🔗 Endpoint List (Rekber System 4 Role)

## 📂 Authentication (Google OAuth)

- `GET /auth/google`
- `GET /auth/google/callback`
- `POST /set-role`
- `GET /profile`
- `GET /logout`

---

## 📂 Buyer

- `GET /rekber/list`
- `POST /transaction/create`
- `GET /transaction/{id}`
- `POST /transaction/{id}/upload-proof`
- `POST /transaction/{id}/confirm-receive`
- `POST /transaction/{id}/cancel`

---

## 📂 Seller

- `GET /transaction/seller-list`
- `GET /transaction/{id}`

---

## 📂 Rekber

- `GET /rekber/transactions`
- `GET /rekber/transaction/{id}`
- `POST /rekber/transaction/{id}/approve-release`
- `POST /rekber/transaction/{id}/hold-fund`

---

## 📂 Admin

- `GET /admin/transactions`
- `GET /admin/transaction/{id}`
- `POST /admin/user/add-rekber`
- `POST /admin/transaction/{id}/force-release`
- `POST /admin/transaction/{id}/resolve-dispute`
- `GET /admin/rekber/list`
- `POST /admin/rekber/{id}/disable`
- `POST /admin/rekber/{id}/enable`

---

## 📂 Notifications (Optional Semua Role Bisa)

- `GET /notifications`
- `POST /notifications/mark-read`

---

Perlu contoh payload tiap endpoint? 🚀
