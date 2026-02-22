# ⚡ 27electricianjob

Modern electrician job script for FiveM built with **ox_lib**, **ox_target** and **ox_inventory**.

---

## 📦 Features

* ⚡ Interactive electrician job
* 🎯 ox_target interaction system
* 📦 ox_inventory item support
* 🔔 ox_lib notifications & UI
* 🔒 Server-side secure rewards
* 🧩 Clean and optimized code structure
* 🚀 Lua 5.4 supported

---

## 📂 Resource Structure

```
27electricianjob/
│── fxmanifest.lua
│
├── client/
│   ├── config.lua
│   └── client.lua
│
├── server/
│   └── server.lua
│
└── shared/
    ├── locales.lua
    └── shared.lua
```

---

## 🔧 Dependencies

Make sure you have installed:

* ox_lib
* ox_target
* ox_inventory

Add them to your server.cfg:

```
ensure ox_lib
ensure ox_inventory
ensure ox_target
ensure 27electricianjob
```

---

## ⚙️ Installation

1. Download or clone the repository.
2. Place the folder into your `resources` directory.
3. Add `ensure 27electricianjob` to your `server.cfg`.
4. Restart your server.

---

## 🛠 Configuration

You can configure job settings inside:

```
client/config.lua
```

Adjust:

* Locations
* Rewards
* Required items
* Timers
* Animations

---

## 🔐 Security

* Rewards handled server-side
* No client-side money triggers
* Optimized for exploit prevention

---

## 🧑‍💻 Author

**27**

Version: 3.1.0-pro

---

## 📜 License

Free to use.
Do not reupload without credit.
