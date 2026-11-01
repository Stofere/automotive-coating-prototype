# ROLE & PROJECT OBJECTIVE
Act as a Principal Automotive UI/UX Designer and Frontend Architect. Design a luxury, high-converting, SEO-optimized bilingual (ID/EN) web interface for **PROTEGO DETAILING (`@protegodetailing`)**, a premier automotive protection studio specializing in **Nano Ceramic / Carbon Matrix Coating, Paint Protection Film (PPF), and Rust Protection** located in **Cipondoh, Tangerang (Near Alam Sutera)**, serving the Greater Jakarta–Tangerang area.

---

# 1. VISUAL IDENTITY & RESTRAINT GUIDELINES ("ARCHITECTURAL LIQUID METAL") PROTEGO LOGO: PROTEGO.png
* **Design Philosophy & Reference Calibration:** 
  * Take inspiration from dark luxury automotive studio layouts (diagonal brushed-metal architectural lines, dramatic overhead light-tunnel reflections on the studio floor, and chamfered/angled metallic buttons) combined with PROTEGO's brushed-silver shield crest.
  * **CRITICAL RESTRAINT RULE:** Keep the aesthetic **refined, architectural, and Porsche/Maybach-grade**. Avoid "over-the-top" gaming/sci-fi neon effects, excessive glowing borders, or cluttered diagonal slashes. Balance sharp geometric diagonal accents (15° angled cuts on buttons and comparison frames) with generous luxury whitespace, clean grids, and authentic workshop photography.
* **Theme Polarity (70% Dark Obsidian / 30% Brushed Alabaster Silver):**
  * **70% Dark Studio Sections:** Deep Obsidian (`#0A0B0D`) and Matte Carbon (`#121418`) with subtle radial silver studio spotlight gradients (`rgba(229, 231, 235, 0.07)`) for the Hero, Before/After Interactive Showcase, PPF/Rust Protection, and Portfolio sections.
  * **30% Brushed Silver Contrast Section:** High-key Brushed Alabaster Silver gradient (`#ECEEF2` to `#FFFFFF`) specifically for the **Coating Packages & Pricing Matrix** section (matching PROTEGO's official silver package sheet and metallic shield background) to maximize pricing readability and trust.
* **Color Tokens:**
  * Primary Dark Surface: `#0A0B0D`
  * Elevated Dark Card: `#14171C` with `1px solid rgba(255, 255, 255, 0.12)` specular border
  * Light Silver Surface: `linear-gradient(135deg, #E5E7EB 0%, #F9FAFB 50%, #D1D5DB 100%)`
  * Primary Metallic Accent: Brushed Chrome Gradient (`linear-gradient(90deg, #9CA3AF 0%, #F3F4F6 50%, #9CA3AF 100%)`)
  * High-Contrast Luxury Accent: Caliper Gold / Exotic Amber (`#F59E0B`) used sparingly for 5-star review badges and subtle active indicators.
  * Text Tokens: Pure White (`#FFFFFF`) and Silver Muted (`#9CA3AF`) on dark backgrounds; Deep Charcoal (`#111827`) and Slate (`#4B5563`) on silver backgrounds.
* **Typography:**
  * **Display / Headings:** Wide, geometric automotive sans-serif (`Syncopate`, `Michroma`, or `Space Grotesk` in uppercase with `0.08em` letter-spacing), echoing the wide geometric lettering of the `PROTEGO` wordmark.
  * **Body & Technical Specs:** `Plus Jakarta Sans` or `Inter` for clean readability across Bahasa Indonesia and English technical terms.

---

# 2. BILINGUAL (ID/EN) & COPYWRITING STRATEGY
* Include a sleek `ID | EN` toggle in the top navigation bar.
* **Default Language (ID - Primary Bahasa Indonesia + English Luxury Terminology):** Keep automotive protection terms in English (*Coating Packages, Carbon Matrix, Italian Paint Correction & Polishing, Swirlmarks & Hologram, Paint Protection Film, Free Pick-Up & Delivery, Home Service*) paired with persuasive, natural Indonesian descriptions.
* **Secondary Language (EN):** Full international English for expat and English-preferred luxury car owners in Alam Sutera, BSD, and Jakarta.

---

# 3. SECTION-BY-SECTION UI/UX LAYOUT & EXACT CONTENT

## Section 1: Sticky Glassmorphic Navigation Bar
* **Left:** PROTEGO 3D Metallic Shield Logo + wide geometric `PROTEGO` wordmark.
* **Center Links:** `Home` | `Our Solution` | `Coating Packages` | `Before & After` | `Reviews` | `FAQ` | `Location`
* **Right Actions:** 
  * Bilingual Switcher (`ID / EN` pill)
  * Chamfered/angled metallic outline button: `BOOK NOW >` (links directly to WhatsApp `087810007123` Kendrew - Protego).

## Section 2: Hero Section (Dark Studio Spotlight + Diagonal Metallic Accents)
* **Visual Composition:** Split or asymmetric full-viewport hero on a dark obsidian studio floor with realistic car reflection and subtle brushed-steel diagonal architectural beams in the background. Showcases an exotic/luxury vehicle (e.g., Maybach / Lamborghini / Porsche) under precision LED light-tunnel inspection.
* **Eyebrow Tag (with vertical silver accent line):** `PREMIUM AUTOMOTIVE COATING, PPF & RUST PROTECTION`
* **Main Headline (ID Default):** `PROTEGO ARMOR: KILAP SEMPURNA & PROTEKSI KELAS SHOWROOM.` (EN: *Advanced coating & PPF protection for a longer-lasting, glossier, and more valuable ride.*)
* **Value Proposition Badges (Glassmorphic Pills):**
  * `✓ FREE Pick-Up & Delivery (Area Jakarta – Tangerang)`
  * `✓ Home Service Available`
  * `✓ Direct Owner QA & Up to 7-Year Warranty`
* **CTAs:**
  * Primary Button (Brushed Silver Metallic Fill with dark text & angled right edge): `EXPLORE OUR SOLUTION >`
  * Secondary Button (Frosted Glass with WhatsApp icon): `FREE CONSULTATION (WHATSAPP)`

## Section 3: Interactive Before & After Proof Showcase (Smooth Left/Right Drag UX)
* **Section Header:** 
  * Eyebrow: `OUR SERVICES & REAL PROOF`
  * Title: `COMPLETE PROTECTION SOLUTIONS`
  * Subtitle (Right-aligned with vertical divider): *Geser ke kiri dan kanan untuk melihat bukti nyata transformasi Italian Paint Correction, Nano Ceramic Coating, dan PPF di studio kami.*
* **3-Column Angled/Parallelogram Interactive Comparison Grid (Inspired by Auto Shield layout, refined for smooth UX):**
  * Each card features a subtle 12° angled architectural frame (or clean rounded-sm luxury frame on mobile) with a **smooth, hardware-accelerated Left-to-Right Drag Handle (`< >`)** that works seamlessly with both finger touch swipe (mobile) and mouse drag (desktop).
  * **Card 1: NANO CERAMIC & CARBON MATRIX COATING**
    * *Before:* Dull, oxidized clear coat with water spots (e.g., 5-year-old daily SUV or classic BMW).
    * *After:* Deep, mirror-like wet gloss with extreme hydrophobic water beading (*efek daun talas*).
  * **Card 2: PAINT PROTECTION FILM (PPF)**
    * *Before:* Vulnerable front bumper/hood exposed to stone chips and road debris.
    * *After:* Invisible self-healing optical-grade urethane armor on a Supercar (Lamborghini Gallardo / Huracan) or Luxury EV (BYD Seal).
  * **Card 3: ITALIAN PAINT CORRECTION & FULL DETAILING**
    * *Before:* Heavy swirlmarks, fine scratches (*baret halus*), and hologram under inspection lights.
    * *After:* Flawless, scratch-free reflections on paint, engine bay, rims, and calipers.
* **Bottom Value Bar (4 Icon Pillars with Diagonal of Parallelogram Metallic CTA):**
  * `🛡️ LONG-LASTING PROTECTION (Up to 7 Years)` | `💎 BRILLIANT MIRROR SHINE (10H Hardness)` | `🚗 ENHANCED RESALE VALUE` | Angled Silver Banner CTA: `DRIVE WITH CONFIDENCE >`
* **CMS Owner UX Note:** Designed so the business owner only needs to upload a `Before_Image` and `After_Image` pair in EmDash CMS, and the component automatically aligns, crops, and powers the `< >` interactive slider.

## Section 4: Official Coating Packages (The 30% Brushed Alabaster Silver Contrast Section)
* **Visual Style:** Transitions into the signature **Brushed Alabaster Silver (`#F4F5F7`)** diagonal background inspired directly by PROTEGO's official package sheet, creating a crisp, authoritative showroom spec-sheet feel.
* **3-Tier Package Cards:**
  1. **SMART PACKAGE**
     * **Technology:** *Using Quartz Coating*
     * **Durability / Warranty:** **3 Years**
     * **Best For:** Daily drivers seeking high-value gloss & protection (*"Pilih paket termurah tapi hasilnya puas banget"*).
  2. **ADVANCED PACKAGE (Popular Choice)**
     * **Technology:** *Using Diamond Coating*
     * **Durability / Warranty:** **4 Years**
     * **Best For:** Deep color enhancement & thicker chemical resistance (Proven on BYD Seal, BMW F30, Mazda CX-5).
  3. **ULTIMATE PACKAGE (Flagship Armor - Highlighted with Dark Obsidian & Chrome Card)**
     * **Technology:** *Using Carbon Matrix Coating / 10H Graphene 3 Layers*
     * **Durability / Warranty:** **7 Years**
     * **Best For:** Maximum thickness, extreme hydrophobic beading, and flagship luxury/new vehicles (Maybach, Geely EX2, Jaecoo J5, Mercedes E-Class).
* **"ALL PACKAGES INCLUDE" Standardized Guarantee Box:**
  * **01. Full Detailing:** *Detailing secara menyeluruh, Mesin (Engine Bay), Exterior, & Interior sampai ke sela-sela.*
  * **02. Italian Paint Correction & Polishing:** *Hilangkan Baret, Swirlmarks & Hologram.*
  * **03. Nano Ceramic Coating Application:** *Polysilazane SiO2 multi-layer application with direct Owner Quality Assurance (QA).*
  * **Complimentary:** **FREE Pick-Up & Delivery Service (Area Jakarta – Tangerang)** + Free Maintenance Consultation.

## Section 5: Influencer Spotlight & Verified Google Maps Social Proof
* **Trust Metrics Bar:** `⭐ 5.0 Rating on Google Maps` | `5+ Years Trusted Expertise` | `Multi-Car Returning Clients (Up to 6 Cars per Owner)`
* **Google Maps Sentiment Filter Pills (Interactive filter tags):**
  * `All Reviews` | `Thick Coating (6)` | `Neat Workmanship (3)` | `Cleanliness (3)` | `Attention to Detail (3)` | `Car Protection (2)` | `Used Car Transformation (2)` | `Quality of Work (2)` | `Results (5)` | `Attention (2)` | `Interior (2)`
* **Dual-Format Social Proof Layout:**
  * **Left Column: Influencer & Video Reels Carousel:** Vertical 9:16 video cards showcasing famous influencers (including `@kepinchocs` / Kevin Anggara) and real walkaround reels of exotic and daily cars under the PROTEGO studio lights.
  * **Right Column: Verified Customer Review Bento Grid (Real Quotes & Car Badges):**
    * *Quote 1 (Exotic & First-Time PPF Trust):* "Sebelumnya belum pernah proteksi mobil, awalnya ragu saat ditawari ppf & coating disini karena brand baru juga. Tapi mereka jelasin bahan yang mereka pake premium, teknik yg mereka gunakan profesional. Dan ternyata hasilnya mengkilap, wet glossy look se mesin mesin nya and mantul semua cahaya di jalan atau lobby mall pelayanan nya serius dan owner turun tangan langsung dan yang paling penting, harganya masih sangat masuk akal dengan kualitas yang didapat. Good job keep it up👍" — **Juan Rama** (*Lamborghini Gallardo* — PPF & Coating).
    * *Quote 2 (5-Year Loyal Client):* "Aku udah percayain protego tuh kayaknya ada ya 5 tahunan. Dari masih awal banget. pelayanannya best bgt!!!! top.. " — **Marceline Tania** (*Maintainance Coating Fortuner & Innova Zennix*).
    * *Quote 3 (6 Cars Protected, Zero Complaints):* "Benar-benar puas dengan hasil kerja Protego. Sudah 6 mobil dikerjakan di sini dan tidak pernah ada komplain sama sekali. Pelayanan cepat dan tanggap. Hasilnya bikin mobil jauh lebih glossy, bahkan untuk mobil yang masih baru, awalnya kira tidak akan ada perbedaan, ternyata terlihat jelas sekaligus lebih terproteksi. Akan terus percayakan ke Protego. Terima kasih. Makin sukses ya.." — **Priska Stephanie**
    * *Quote 4 (Used Car Transformation):* "Puas banget sama hasilnya! Mobil Toyota Rush gue usianya udah mau 5 tahun, jujur tadinya tampilannya udah mulai buluk dan kusam. Tapi setelah dibawa ke Protego buat coating, gila sih... balik kinclong lagi kayak baru keluar dealer! Kerjaannya rapi dan detail. Highly recommended buat yang mau nyegerin tampilan mobil lama." — **Teguhku** (*Coating Toyota Rush*)
    * *Quote 5 (Used Car Transformation):* "Pengerjaan-nya Top Quality, Jujur puas banget
    Habis di coating, mobil lama berasa jadi mobil baru lagi dan Totally Recommended untuk Coating di-sini." — **Calvin Perez** (*Coating Honda Brio*).
    * *Quote 6 (10H Graphene 3-Layer):* "Hasil coatingnya overall bagus dan detail..
    Saya ambil paket 10H Graphene 3 Layers. Thank you ko kendrew n mas reza" — **Jason Imanuel** (*White car with protective coating*).
    * *Quote 7 (10H Graphene 3-Layer):* "Ambil paket 3 layers 10 H. Coatingnya detail. Servicenya ok. Pas tau mau nunggu d workshop, malah d kasih lunch sbg complimentary. Wowww.." — **Kris** (*Jaecoo J5*)
    * *Quote 8 (Thick Coating):* "Kualitas pekerjaan rapi dan memuaskan, coating tebal dan detailnya dapet. Bahkan kemarin langsung di QA sama owner-nya. Recommended pokoknya!" — **Aan Priandana** 
    * *Quote 9 (10H Graphene 3-Layer):* "Pelayanan terbaik.. Mobil di jemput dan di antar kembali.. Ambil paket coating 10H 3 Layers..
    Hasil coating rapi dan detail..
    Ga percuma jauh jauh dari Bogor ke Protego..👍🏼👍🏼" — **Zifco Istian Hidayah**
    * *Quote 10 (1-Year Durability & Home Service):* "Coating sudah 1 tahunan dan hasilnya masih kinclong. Sayapun dimanjakan dengan fitur home service yang anti ribet. Highly recommended." — **Boby Gunawan** (*Mercedes-Benz E-Class*).

## Section 6: Studio Experience, FAQ & Direct WhatsApp Footer
* **The PROTEGO Workshop Standard:** Highlight the physical studio in **Cipondoh, Tangerang (Near Alam Sutera)**—proper dust-free lighting bay, comfortable air-conditioned waiting lounge, kids-friendly environment, and direct educational consultation with the owner.
* **Interactive Booking Card:**
  * Quick selectors: `Select Package (Smart 3Y / Advanced 4Y / Ultimate 7Y / PPF / Rust Protection)` + `Car Model` + `Service Type (Studio Visit / Free Pick-Up & Delivery Jakarta-Tangerang / Home Service)`.
  * Clicking **"Book & Consult via WhatsApp"** auto-generates a structured message to **`087810007123`**.
* **Embedded Dark-Mode Google Map:** Direct route button to `PROTEGO DETAILING | Coating, PPF & Rust Protection Tangerang City`.