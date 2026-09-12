# Features and how to use them

Bolkar BIZ is one app. Menus can hide if your **business type** does not need them (for example a pure salon vs a grocery). If something is missing, check shop / business-type settings.

Voice examples below are typical. Speak in the language you set in the app (English, Hindi, and other supported locales).

---

## 1. POS / billing

**What it is:** Counter sales — items, qty, tax, discount, payment.

**How to use**

1. Open **New bill** / POS.
2. Add lines: search, barcode camera, or voice.
3. Discount or tax as allowed by your role.
4. Choose **Cash / UPI / Card / Credit**.
5. Complete. Print, PDF, or share if you use those.

**Useful details**

- Hold a bill if the customer will add more items.
- Credit sale attaches to a customer; collect later from their ledger.
- Void / return only if your role allows it — ask the owner to enable.

**Voice:** *“Start a bill.”* *“Add 2 kg rice.”* *“Pay by UPI.”*

---

## 2. Inventory and catalogue

**What it is:** Products, categories, stock on hand, low-stock.

**How to use**

- **Add product:** name, sale price, unit, optional barcode and cost.
- **Stock in:** purchase or opening stock so billing can decrement.
- **Adjust:** damage, count correction.
- **Categories / brands:** keep the POS grid scannable.

**Useful details**

- Negative stock: allowed or blocked depending on settings — set this before staff go live.
- Desktop is faster for bulk catalogue; phone is fine for a few SKUs.
- Camera barcode is an Android/iOS convenience; Windows often uses a USB scanner as keyboard input.

**Voice:** *“How much Maggi is left?”* *“Add 20 Pepsi to stock.”*

---

## 3. Customers

**What it is:** People who buy from you — phone, dues, history.

**How to use**

1. Create from the customer screen or from a bill.
2. Attach the customer on credit sales.
3. Open the customer to see past bills and balance.

**Useful details**

- Mobile number is the usual unique key. Enter it carefully.
- Don’t store card PANs; UPI/card go through the method you already use.

---

## 3b. Customer credit limit (udhari)

**What it is:** A rupee cap per customer for credit sales. The counter can sell without cash today; the app tracks used vs remaining limit.

**How to use**

1. Open the customer.
2. Set **credit limit** (and optional billing cycle if your shop uses one).
3. On POS, attach that customer and pay with **Credit / udhari** (after wallet or gift card if you use those).
4. Collect later from the customer ledger / outstanding report.
5. When they repay, record the collection so the used amount drops.

**Useful details**

- If the bill would go **over the limit**, the app should warn or block — train cashiers not to override without the owner.
- Credit is per customer, not a shop-wide “everyone can take udhari.”
- Voice: *“Anuj ka udhari khata banao, limit 5000.”* *“Bill udhari se.”*

---

## 4. Services and bookings

**What it is:** Time-based work — salon chairs, repair jobs, appointments.

**How to use**

1. Define **services** (haircut 30 min, ₹250).
2. Open **bookings / calendar**.
3. Pick customer, service, staff, time.
4. Convert completed work to a bill.

**Useful details**

- Mixed shops (spa + retail products) keep both catalogue and services.
- Reminders depend on notification permission on the device.

**Voice:** *“Book Priya for facial tomorrow 4 pm.”*

---

## 4b. Laundry and workshop pickup / drop

**What it is:** Jobs that leave the shop: collect from home or drop processed items back. Typical for **laundry, dry-clean, tailoring, repair workshops**.

**How to use**

1. Set business type / processing workflow so laundry or workshop stages are on.
2. Create an order: customer, items/garments, **pickup** time/address.
3. Assign a **driver** (they use the Android Driver app).
4. Process in shop stages (received → washing / repair → ready).
5. Schedule **drop** / delivery; driver marks delivered.

**Useful details**

- Pickup and drop are logistics on top of the job — not a replacement for POS retail.
- Owner/manager assigns runs in Bolkar BIZ; the rider only sees their jobs in **Driver - For BolkarBIZ**.
- Voice: *“Laundry pickup book karo.”* *“Dipti ke kapde ready hue?”*

---

## 4c. Driver app

**What it is:** Android-only field app for assigned pickups and deliveries.

**How to use**

1. Owner creates a driver / delivery staff user in Bolkar BIZ.
2. Driver installs [Driver - For BolkarBIZ](https://play.google.com/store/apps/details?id=com.bolkarbiz.driver&hl=en_IN).
3. Driver goes online, accepts the run, navigates, marks picked / dropped.

**Useful details**

- Not a billing app. No iOS driver build.
- Keep the owner account off the rider’s phone.

---

## 5. Voice and chat AI

**What it is:** Operator assistant. Core commands work **offline**. Cloud AI may add richer answers when online.

**How to use**

1. Grant **microphone** if you want voice (optional).
2. Open the AI / assistant panel.
3. Speak or type a shop command, not a general chat question.

**Good commands**

- Create / find products
- Start or add to a bill
- Stock questions
- Simple reports (*“Today’s sales”*)

**Useful details**

- The assistant should **show what it will change** before destructive actions. Confirm if it asks.
- Photos (product image, bill image) need camera and, when used, may call online analysis.
- Large on-device models need extra disk; they are optional.

---

## 6. Team and roles

**What it is:** Who can bill, who can see profit, who can delete.

**How to use**

1. Owner opens **team / staff**.
2. Add person (phone / login).
3. Assign a role.
4. Staff install the app and sign in.

**Useful details**

- Cashier: POS + maybe customers.
- Manager: stock, most reports, staff of the counter.
- Owner: settings, tax, destructive deletes.

Never share the owner password on the cashier PC.

---

## 7. Reports and analytics

**What it is:** Today / period sales, items, taxes, outstanding.

**How to use**

- **Today** after close: cash vs UPI vs credit.
- **Item** report: what to reorder.
- **Customer** dues: who to collect from.

**Useful details**

- Reports on this device include local unsynced bills. Another branch may lag until sync.
- Export / print from desktop when you need accountant copies.

**Voice:** *“Sales today.”* *“Top items this week.”*

---

## 8. Payments you already use

Bolkar BIZ records **how** the customer paid. Card numbers are not stored as PAN/CVV. UPI is typically “mark as UPI” plus your existing QR. Optional hardware (printer, NFC) is OS-permission based.

---

## 9. WhatsApp commerce (optional)

**What it is:** Sell and support on **your** WhatsApp Business number. Bolkar BIZ does not take over the customer’s chat as a shared inbox you do not own.

**How to use**

1. Connect WhatsApp Business in shop settings (Meta / WhatsApp terms apply).
2. Share catalogue, bill PDF, or order updates from the customer or bill screen.
3. Incoming orders (if enabled for your plan) land as shop jobs you confirm in Bolkar BIZ.

**Useful details**

- This is **seller-owned** commerce: your number, your customers.
- Staff who send WhatsApp messages must be trained; chats are personal data (see the privacy policy).
- You can run WhatsApp **together with** a website or custom app — it is not either/or.

---

## 9b. Your own website or mobile frontend

**What it is:** Some sellers already have (or will build) a **frontend-only** site or customer app — their brand, their UI. Bolkar BIZ stays the **business OS**: catalogue, stock, billing, customers, staff, pickup jobs.

**How to use**

1. Keep operating in Bolkar BIZ (this is the system of record).
2. Point your storefront or app at Bolkar BIZ APIs / catalogue you already manage here.
3. Do **not** duplicate stock in a second admin. Staff still bill, receive, and close day in Bolkar BIZ.

**Useful details**

- You own the customer-facing UI. We do not force a Bolkar-branded shop website.
- Desktop/mobile Bolkar BIZ remains how the team runs the shop; the custom frontend is for buyers if you want one.
- Talk to support@bolkarbiz.com if you need the integration path for a new storefront.

---

## 10. Offline and sync

| Situation | What happens |
|---|---|
| Airplane mode / tower down | Bill, stock on **this** device, local AI |
| Back online | Queue syncs to the shop cloud |
| Two counters, both offline | Each till has its own unsynced bills until they reconnect |

Do not copy the app’s data folder by hand between PCs.

---

## Permissions (only when you use the feature)

| Permission | Used for |
|---|---|
| Camera | Barcode, product photo, document |
| Microphone | Voice commands |
| Storage / files | Backups, images, AppImage extras |
| Bluetooth | Optional printers / peripherals |
| Notifications | Booking and sync alerts |

Privacy: https://bolkarbiz.com/privacy-policy
