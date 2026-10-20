**The ultimate player-owned vehicle dealership experience for FiveM servers.** Ak47 Cardealer brings a complete dealership economy to your server with in-game dealership creation, 3D showroom displays, and a streamlined NUI vehicle manager. Players can preview vehicles in interactive catalogues, take timed test drives with automated key handling, and finance vehicle purchases with automated recurring bank payments and repossession. Powered by `ak47_lib`, it guarantees seamless plug-and-play performance across ESX, QBCore, and Qbox frameworks.

---

## 🎥 Showcase
<img width="1920" height="1080" alt="thumbnail" src="https://github.com/user-attachments/assets/06ae35ff-682d-4adc-b864-9a5e75f87a9b" />

> **[Click here to watch the full feature showcase on YouTube](https://youtu.be/irBXgRX5rMU)**

---


## 🔥 Key Features

Designed to improve roleplay immersion and economy balancing:

### 🏢 In-Game Dealership & Showroom Creator

* **Interactive Dealership Creation:** Administrators can create complete dealerships on the fly using `/createdealer`, defining custom PolyZone perimeters, boss zones, catalogue terminals, and specific spawn points for catalogue previews, purchases, and test drives without restarting the server.
* **Multi-Vehicle Dealership Types:** Full native support for automobile, motorcycle, boat/marine, aircraft, and helicopter dealerships with specialized water-level placement and tailored preview zones.
* **Dynamic Display Spots:** Add showroom display locations anywhere with `/adddisplay`, allowing admins and managers to place, reposition, or delete display stands interactively.

### 🚗 Interactive Display Vehicles & 3D Showroom

* **360° Turntable Rotation:** Display vehicles can smoothly rotate in place with configurable rotation speed, creating an authentic luxury showroom aesthetic.
* **Live Vehicle Swapping & Tuning:** Dealership staff can swap out display vehicles directly from available stock, adjust vehicle color combinations, configure liveries, and toggle vehicle extras on the spot.
* **Interactive 3D Target & Floating HUD:** Customers can interact with display vehicles via target or 3D text to view vehicle models, pricing, VIP availability, and test drive or purchase options.

### 💳 Automated Financing & Economy Control

* **Flexible Vehicle Financing:** Customers can purchase vehicles outright or finance them with customizable down payments, interest rates, and installment periods.
* **Automated Weekly Deductions & Repossession:** The server runs automated background installment deductions for online and offline players. If a player fails to pay after consecutive missed cycles, the vehicle is automatically repossessed and deleted from the database.
* **Phone Mail Notifications & Society Payouts:** Sends automated SMS/mail alerts via qs-smartphone or gksphone for payment confirmations and repo warnings, while routing sales and down payment commission cuts directly into the dealership's society bank.

### 🏎️ Interactive Catalogue & Timed Test Drives

* **Immersive 3D Catalogue:** Customers can browse categorized dealership stock with live vehicle camera warping, allowing players to sit inside and inspect vehicles before buying.
* **Timed Test Drive with Smart Keys:** Customers or staff can take vehicles for timed test drives featuring on-screen countdowns, automatic temporary virtual key distribution, full fuel allocation, and return markers.
* **Safe Vehicle Return & Anti-Abuse:** Teleports the player and deletes the test vehicle if time expires or if the customer wanders too far, cleanly restoring them to the showroom floor.

### 👑 VIP Loyalty System & Dealership Boss Menu

* **VIP Customer Management:** Dealers can register nearby players as VIP members with custom discount percentages, offering VIP-exclusive vehicles and deals.
* **Comprehensive Boss Settings:** Dealership owners can configure profit commission percentages, manage VIP discount caps, toggle direct catalogue selling, and manage employees via integrated boss menus.

### 🛠️ Technical Excellence

* **Multi-Framework & Target Support:** Seamlessly works with ESX, QB, QBX, and various target systems (ox_target, qb-target, qtarget).
* **Highly Secure:** Built-in server-side exploit checks, including distance validation and trigger authentication, to prevent cheating.
* **Automated Database Setup & Rich Integrations:** Automatically builds all required SQL tables on startup, generates unique plates, logs transactions to Discord webhooks, and connects with phone systems (qs-smartphone, gksphone) and t1ger_mechanic.

---

## 💻 Framework:

* ESX, QB, QBX

---

## ⚙️ Dependencies:

* ak47_lib: https://github.com/MenanAk47/ak47_lib/releases/latest

---

## ⚙️ How To Install:

* Download ak47_cardealer from your cfx portal.
* Add the script in your resources folder.
* Add items based on your framework instruction.
* Add item images into inventory.
* Start the script in your server.cfg below framework files.
* Make sure you have all dependencies.
* Restart the server.

---

## 🔗 Links & Support:

* **📖 Documentation:** [https://docs.menanak47.com/multi-framework/ak47_cardealer](https://docs.menanak47.com/multi-framework/ak47_cardealer)
* **🛒 Buy Now (Tebex):** [https://menanak47.tebex.io/package/5775303](https://menanak47.tebex.io/package/5775303)
* **💬 Discord Support:** [https://discord.gg/menanak47](https://discord.gg/menanak47)

---

## 📝 Note:
* We don't support custom framework. Make sure you are using official framework update.
* Renaming the script is not allowed. It may break the functionalities.
* Don't upload the script with FileZilla, Use Winscp if you are using FTP for file uploading
