# E-commerce-Kigalux-app-ui-ux-prototype

**Course:** INSY 8313 – Management Information System (MIS)
**Institution:** Adventist University of Central Africa
**Instructor:** Eric Maniraguha
**Assessment:** Group Assignment IV-a – E-Commerce / Web Application UI/UX Design Using Figma

---

## Group Details

* **Member 1:** IRADUKUNDA Gendre Patient | **Reg No:** 20252SEN117
* **Member 2:** NKUBA Hopson Sun Star | **Reg No:** 20252NET086

---

## 1. Selected System & Figma Link

* **Selected Application:** E-Commerce Mobile Application — a marketplace supporting and promoting local Rwandan tailors and "Made in Rwanda" fashion, connecting them to a national and international audience
* **Public Figma Link:** https://www.figma.com/design/ffbH6EtJLbs2BryYIZMD49/E-commerce-app?node-id=0-1&t=BPs8wzciEvZAKr8K-1
* **Public Github repo Link:** https://github.com/iradukundagendrepatient-cmd/E-commerce-Kigalux-app-ui-ux-prototype
  

---

## 2. Problem Statement

Local Rwandan tailors and fashion designers create original, high-quality, culturally rich clothing and art, but most lack a dedicated digital platform to showcase and sell their work beyond their immediate physical location. This limits their income, visibility, and ability to compete with mass-produced, imported clothing.

Our mobile e-commerce application solves this by giving local tailors a dedicated marketplace to display and sell their "Made in Rwanda" designs directly to customers — locally and internationally. The platform is built around discovery (browsing designers and their collections), trust (clear product and maker information), and a simple, low-friction buying experience.

**Target users:** Anyone interested in authentic, locally made Rwandan fashion — from local customers in Kigali and beyond to the diaspora and international buyers who want to support and access genuine Rwandan-designed clothing and craftsmanship. The audience is broad and not limited by age, occupation, or location.

**Why it matters:** The platform directly supports the "Made in Rwanda" initiative by giving local tailors and designers a wider market reach, helping grow their businesses, preserve and promote Rwandan textile art and craftsmanship, and increase national pride in locally made products on a global stage.

---

## 3. User Persona

### Persona 1: Alex M. (Customer)

* **Age:** 24
* **Occupation:** University Student & Part-Time Content Creator
* **Location:** Kigali, Rwanda

**Goals:**
* Discover and buy authentic, locally designed Rwandan clothing on mobile.
* Learn a bit about the tailor/designer behind each product before buying.
* Complete secure checkout quickly, whether shopping locally or internationally.

**Frustrations & Challenges:**
* Difficulty finding genuine, locally made fashion online — most marketplaces favor imported brands.
* Cluttered interfaces with tiny, hard-to-tap buttons.
* Not knowing whether a listed product is truly Rwandan-made.

### Persona 2: Uwase D. (Local Tailor / Designer)

* **Age:** 34
* **Occupation:** Independent Fashion Designer & Tailor
* **Location:** Kigali, Rwanda

**Goals:**
* Showcase her clothing designs and craftsmanship to a wider, even international, audience.
* Grow her small tailoring business beyond word-of-mouth and local foot traffic.
* Build a recognizable, trusted profile/brand within the platform.

**Frustrations & Challenges:**
* Limited digital presence and marketing skills/tools.
* No easy way to reach customers outside her local area.
* Competing with cheaper imported clothing that overshadows local craftsmanship.

---

## 4. User Flow Diagram

```
[ Splash / Onboarding ] ──> [ Login / Register ] ──> [ Home / Catalog Feed ]
                                                              │
                                                              ▼
[ Order Confirmation ] <── [ Payment / Checkout ] <── [ Product Details ]
                                      ▲                       │
                                      └─────── [ Cart ] ──────┘
```

**Flow explanation:** A new user lands on the splash/onboarding screen, logs in or registers, then browses the home catalog featuring collections from local Rwandan tailors and designers. Selecting a product opens the Product Details screen — which includes maker/designer information — from which items are added to the Cart. The user proceeds to Payment/Checkout and, upon success, reaches the Order Confirmation screen.

---

## 5. Wireframes (Low-Fidelity Design)

Minimum 4 structural layouts, focused on layout hierarchy and navigation rather than visual styling:

1. **Onboarding / Login** – Minimalist layout for user authentication (email/phone, password, sign-in, register, guest option).
2. **Home / Catalog Screen** – Search bar, category filters (e.g. traditional wear, modern designs, accessories), featured local tailors banner, product grid.
3. **Product Details Screen** – Image placeholder, title, price, tailor/designer name and short profile, description, quantity selector, Add to Cart CTA.
4. **Shopping Cart / Checkout Screen** – Item summary, quantity toggles, subtotal/shipping breakdown, payment method selection, Confirm Order button.

*(Exported as PNG and stored in the `wireframes/` folder.)*

---

## 6. High-Fidelity UI Design

Minimum 6 polished screens, applying color, typography, icons, images, and consistent spacing:

1. Onboarding / Splash Screen
2. Login & Sign Up Screens
3. Home Screen / Product Catalog
4. Product Details Screen
5. Shopping Cart Screen
6. Checkout / Payment Confirmation Screen

**Typography:** Clean, legible sans-serif type hierarchy for strong readability across screen sizes.

**Color Palette:** High-contrast primary colors used to emphasize interactive elements (buttons, active tabs, floating actions).

**Dark Mode Variant:** A complete high-fidelity dark mode alternative is included for improved accessibility and comfort during night use.

*(Exported as PNG and stored in the `high-fidelity-designs/` folder.)*

---

## 7. Assets

UI icons, logos, and custom graphics exported in SVG format and stored in the `assets/` folder (cart, search, user, and navigation icons; branding elements; category images/banners).

---

## 8. Key Features Implemented

* Interactive onboarding and registration workflow.
* Category filtering and quick search bar navigation for browsing local designs.
* Tailor/designer profile information displayed on each product to build trust and visibility.
* Interactive cart quantity controls with live price calculation.
* Multi-screen dark mode switch demonstration.
* Clickable interactive prototype with connected component frames and screen transitions.

---

## 9. Accessibility Considerations

* **Contrast Ratios:** Text and icon fills meet standard contrast guidelines against both light and dark backgrounds.
* **Touch Targets:** Buttons and navigation icons follow recommended minimum tap-target sizes for mobile use.
* **Visual Hierarchy:** Distinct font weights and sizes clearly distinguish headings, subheadings, and body content.
* **Navigation:** Bottom navigation bar for easy single-thumb reachability on mobile.

---

## 10. Challenges Faced & Conclusion

**Challenges Faced:**
* Organizing large component libraries and managing dark/light variant pairs efficiently within Figma.
* Defining seamless prototype connection paths for multi-screen overlays and bottom modal sheets.

**Conclusion:**
This UI/UX prototype supports the promotion of local Rwandan tailors and "Made in Rwanda" fashion by giving them a clear, accessible digital storefront to reach a national and international audience. Beyond solving common mobile shopping friction points, the design focuses on building trust and visibility for local designers through clarity, accessible visual design, and efficient navigation — demonstrating a practical, user-centered approach to design that also carries real economic and cultural value for local artisans.
