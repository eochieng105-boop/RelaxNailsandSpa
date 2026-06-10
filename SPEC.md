# Relax Nails and Spa - Website Specification

## 1. Project Overview

**Project Name:** Relax Nails and Spa Website  
**Project Type:** Single-page responsive website  
**Core Functionality:** Showcase services, testimonials, location/hours, and provide booking CTAs for a premium nail salon in Delano, CA  
**Target Users:** Local customers seeking nail services, particularly those planning special events (Quinceañeras, family gatherings), looking for wheelchair-accessible and family-friendly spa experiences

---

## 2. UI/UX Specification

### Layout Structure

**Page Sections (in order):**
1. **Navigation Bar** - Fixed top, transparent → solid on scroll
2. **Hero Section** - Full viewport height with background image
3. **About / Why Choose Us** - Split layout with image + text
4. **Services & Pricing** - Card grid layout
5. **Testimonials** - Carousel/grid of customer reviews
6. **Location & Hours** - Map placeholder + schedule
7. **Footer** - Contact info, social links, booking CTA

**Responsive Breakpoints:**
- Mobile: < 768px (single column, stacked layouts)
- Tablet: 768px - 1024px (2 columns where applicable)
- Desktop: > 1024px (full multi-column layouts)

### Visual Design

**Color Palette:**
- Primary Background: `#FDF8F6` (warm off-white/cream)
- Secondary Background: `#FFFFFF` (pure white for cards)
- Primary Accent: `#D4A5A5` (dusty rose/blush pink)
- Secondary Accent: `#B89585` (warm taupe)
- Text Primary: `#2D2A26` (warm charcoal)
- Text Secondary: `#6B6560` (muted brown-gray)
- Highlight/Gold: `#C9A86C` (soft gold for stars/badges)
- Success/Sanitary: `#8FBC8F` (sage green for cleanliness mentions)

**Typography:**
- Headings: `Playfair Display` (serif, elegant, luxurious)
- Body: `Lato` (clean sans-serif, highly readable)
- Font Sizes:
  - H1: 56px desktop / 36px mobile
  - H2: 42px desktop / 28px mobile
  - H3: 24px desktop / 20px mobile
  - Body: 16px
  - Small: 14px

**Spacing System:**
- Section padding: 100px vertical desktop / 60px mobile
- Container max-width: 1200px
- Card padding: 32px
- Element gaps: 24px standard, 48px between major elements

**Visual Effects:**
- Box shadows: `0 8px 32px rgba(45, 42, 38, 0.08)` for cards
- Border radius: 16px for cards, 50px for buttons
- Hover transitions: 0.3s ease for all interactive elements
- Subtle parallax on hero image
- Fade-in animations on scroll for sections

### Components

**Navigation:**
- Logo (text-based "Relax Nails & Spa")
- Links: About, Services, Reviews, Contact
- CTA Button: "Book Now" (links to Instagram)
- Mobile: Hamburger menu with slide-out drawer

**Hero Section:**
- Full-screen background image with subtle dark overlay for text readability
- Main title + subtitle
- 4.8-star rating badge with star icons
- Primary CTA button: "Book an Appointment" → Instagram DM link

**About Section:**
- Left: Image of salon interior
- Right: Text blocks highlighting:
  - Clean, sanitary environment (sterile packaged tools)
  - Wheelchair accessible
  - Family/group-friendly (Quinceañeras, family dates)
  - Zero-wait / fast service
  - Complimentary bottled water

**Services Cards:**
- Card layout in 2x2 grid (desktop) / single column (mobile)
- Each card: Image, service name, price range, brief description
- Services to feature:
  1. Manicures & Full Acrylic Sets ($20 – $60+)
  2. Premium Freestyle Nail Art & Custom Designs ($60 – $140+)
  3. Luxury Pedicures & Foot Massages ($40 – $100)
  4. Brow Waxing & Extensions
- Special highlight: Deluxe Pedicure ($58) with features listed
- Birthday discount callout

**Testimonials:**
- Grid of 4 review cards
- Each: Quote text, customer name, star rating
- Beautiful quote marks as decorative element

**Location & Hours:**
- Two-column layout: Contact info + Hours
- Phone link: tel:+16613727044
- Hours displayed in clean list format for each day
- Instagram/FB links with icons

**Footer:**
- Dark background (`#2D2A26`)
- Logo, brief tagline
- Quick links
- Social media icons
- Copyright

---

## 3. Functionality Specification

### Core Features
- Responsive navigation with scroll-aware styling
- Smooth scroll to sections on nav link click
- Mobile hamburger menu with animated toggle
- Interactive service cards with hover effects
- Testimonial display (static grid for simplicity)
- Direct linking to Instagram for booking
- Click-to-call functionality on phone links

### User Interactions
- Nav links scroll smoothly to corresponding sections
- CTA buttons open Instagram in new tab
- Phone number triggers phone app on click
- Cards have subtle lift effect on hover
- All images have proper alt text for accessibility

### Data Handling
- All content is static/hardcoded
- No backend required
- External links open in new tabs with rel="noopener"

---

## 4. Acceptance Criteria

### Visual Checkpoints
- [ ] Hero section displays with background image, title, rating badge, and working CTA
- [ ] Navigation is fixed, transitions from transparent to solid on scroll
- [ ] About section shows salon interior image with feature list
- [ ] Services grid displays 4 service cards with images and pricing
- [ ] Testimonials show 4 review cards with quotes and customer names
- [ ] Location section shows hours in readable format
- [ ] Footer contains all social links and contact info
- [ ] All external links work correctly (Instagram, Facebook, phone)
- [ ] Layout is fully responsive on mobile (< 768px)
- [ ] Color scheme matches specified palette (blush pinks, warm neutrals)
- [ ] Typography uses Playfair Display for headings, Lato for body

### Functionality Checkpoints
- [ ] Mobile menu opens/closes correctly
- [ ] Smooth scroll works on nav link clicks
- [ ] All buttons and links have appropriate hover states
- [ ] Page loads without console errors

---

## 5. Image Assets

**Available in /public folder:**
- `hero-image.jpeg` - Hero section background
- `pedicure.jpeg` - Pedicure service image
- `inside-spa.jpeg` - About section / interior image
- `N1.jpeg` - Nail art/acrylic set image
- `N2.jpeg` - Manicure image
- `N3.jpeg` - Additional nail service image
- `N4.jpeg` - Additional nail service image

---

## 6. Content Specification

### Hero Section
- **Title:** Relax Nails and Spa
- **Subtitle:** Delano's Premium Nail Salon – Where Perfection Meets Relaxation.
- **Rating Badge:** ★ 4.8 Stars (181+ Reviews)

### About / Why Choose Us Copy
"Our salon offers an immaculate, serene environment where cleanliness meets luxury. We proudly provide wheelchair-accessible facilities and welcome families, groups, and special event parties including Quinceañeras. Experience our signature zero-wait service, where every guest receives complimentary bottled water, great music, and access to our dedicated photo backdrop area for capturing your beautiful new nail sets."

### Services Content
1. **Manicures & Full Acrylic Sets** - $20 – $60+ - Classic to bold acrylic applications
2. **Premium Freestyle Nail Art & Custom Designs** - $60 – $140+ - Artistic expressions by our master artists
3. **Luxury Pedicures & Foot Massages** - $40 – $100 - Indulge in relaxation
4. **Deluxe Pedicure** - $58 - Deep massage, wax mask, sugar scrub, scented cream, lavender infuser
5. **Brow Waxing & Extensions** - Frame your face perfectly

### Testimonials
1. "The place is very clean and organized... The staff is soooo friendly and sweet! They treat us so well and always ask how my family is doing." – Julie A.
2. "Michael listens very well and exceeded my expectations. He's super precise and did the design so perfect! They also gave me a free water and have a cute backdrop setup for photos!" – Phantasya T.
3. "Best pedi/foot massage I've ever had, Kai was amazing... deep massage, wax mask, sugar scrub, lavender infuser, it was all the works!" – Coral O.
4. "Relax Nail is very professional, friendly and sanitary. Everything is packaged and sterile." – Lydia C.

### Hours
- Monday – Wednesday: 9:00 AM – 7:00 PM
- Thursday – Friday: 9:00 AM – 7:00 PM
- Saturday: 9:00 AM – 6:30 PM
- Sunday: 10:30 AM – 5:00 PM

### Contact Links
- Phone: tel:+16613727044
- Instagram: https://www.instagram.com/relaxnailsspa1206/
- Facebook: https://web.facebook.com/people/Relax-nails-spa/61556460280655/