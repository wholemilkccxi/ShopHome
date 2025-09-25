# ShopHome
Multi page html checkout basket blog?
1️⃣ Front‑End – the shop UI
a) Project layout
wholemilk/
│   index.html            ← home / product listing
│   product.html          ← template for a single product (optional)
│   cart.html             ← shopping‑basket view
│   checkout.html         ← checkout form
│   thankyou.html         ← order confirmation page
│
├─ assets/
│   ├─ css/
│   │    main.css
│   │    cart.css
│   ├─ js/
│   │    catalog.js      ← product data (JSON)
│   │    cart.js         ← cart logic
│   │    checkout.js
│   └─ img/
│        product‑01.jpg
│        product‑02.jpg
│        …
└─ data/
     products.json       ← master list of products (id, name, price, img, desc)