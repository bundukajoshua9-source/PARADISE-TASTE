# Paradise Taste

A five-page restaurant website for **Paradise Taste**, a home-style Sierra Leonean restaurant in Freetown, Sierra Leone. This project was built for the **DCOMP 204 Web Design** assignment at Limkokwing University of Creative Technology, Sierra Leone.

---

## Table of contents

1. [Project overview](#1-project-overview)
2. [Purpose and target audience](#2-purpose-and-target-audience)
3. [Pages of the website](#3-pages-of-the-website)
4. [Features shared by all pages](#4-features-shared-by-all-pages)
5. [Technologies used](#5-technologies-used)
6. [Project structure](#6-project-structure)
7. [How the code works](#7-how-the-code-works)
8. [Design choices](#8-design-choices)
9. [How to run the project](#9-how-to-run-the-project)
10. [How to edit the pages](#10-how-to-edit-the-pages)
11. [How to upload changes to GitHub](#11-how-to-upload-changes-to-github)
12. [Possible future improvements](#12-possible-future-improvements)
13. [Author](#13-author)

---

## 1. Project overview

Paradise Taste is a restaurant that opened in 2024 in Freetown. It offers home-style cooking made fresh every day with ingredients from local markets and farmers, at fair prices.

The website was planned in stages: a proposal, research, wireframes, a Figma design, and then the coded pages. It has five pages: **Home, About, Services, Menu and Contact**. They share the same header, footer, colours and fonts so the site looks like one brand.

## 2. Purpose and target audience

**Purpose:** To introduce the restaurant, show what it offers and what it costs, and make it easy to book a table or get in touch.

**Target audience:**
- People living or working in Freetown looking for a clean, reliable place to eat
- Families and groups who need seating or catering
- Customers who want to see services and prices before visiting

## 3. Pages of the website

### 3.1 Home page (`index.html`)
The first page visitors see. It gives a quick summary of the restaurant and sends people to the other pages.

- **Opening banner:** a short notice showing the opening hours
- **Main heading:** "Fresh Sierra Leonean meals, cooked daily in Freetown", with a short sentence about dining in, taking away or getting food delivered
- **Two buttons:** *Reserve a table* (goes to the Contact page) and *See menu and prices* (goes to the Menu page)
- **Main photo:** a picture of the restaurant or its food
- **"Today at Paradise Taste" card:** quick details such as opening times, delivery and payment
- **"What we offer":** four cards for Dine-in, Takeaway, Delivery and Catering, each with a one-line description
- **"Popular Dishes":** three featured dishes with a photo and price (Jollof rice with chicken, Cassava leaves with rice, Grilled fish with plantain), plus a link to see more
- **"How to book a table":** three simple steps: choose a date, time and number of guests; enter your name and phone number; get a confirmation
- **Footer** with the address

### 3.2 About page (`about.html`)
Tells visitors who the restaurant is and what it stands for.

- **About Paradise Taste:** a short paragraph explaining that the restaurant opened in 2024 to give people in Freetown a clean, reliable place to enjoy home-style cooking at fair prices
- **Large photo** of the dining room
- **At a glance:** four cards, each with a photo beside it:

| Number | Label |
| --- | --- |
| 2024 | Year opened |
| 250 | Seats |
| 95 | Members |
| 500 | Menu Items |

- **What we stand for:** four cards explaining the restaurant's values:

| Value | Meaning |
| --- | --- |
| Freshness | Food is cooked fresh daily with locally sourced meats, vegetables and authentic spices from Sierra Leone |
| Fair price | All prices are shown in full on the website |
| Hygiene | Staff follow food safety and kitchen cleaning routines every shift |
| Local sourcing | Vegetables, fish and rice come from Freetown markets |

### 3.3 Services page (`services.html`)
Explains everything the restaurant offers and how each service works.

- **Heading:** "Everything we offer, with timings and how each service works"
- **Four service cards:**

| Service | Details |
| --- | --- |
| Dine-in | 250 seats. Booking is advised on Fridays and Saturdays |
| Takeaway | Ready in 15 to 20 minutes. Pay when you collect |
| Delivery | Freetown only. Price depends on distance |
| Catering | For 10 or more guests. Order 48 hours ahead |

- **Book a table button** that links to the Contact page

### 3.4 Menu page (`menu.html`)
Shows the full food and drink list with prices, so customers know what they will pay before they come. The dishes are grouped into three sections:

| Section | Items |
| --- | --- |
| **Main dishes** | Jollof rice with chicken, Cassava leaves with rice, Groundnut stew with rice, Grilled fish with plantain |
| **Sides** | Fried chips, Mashed potatoes, Side salad, Shrimp salad |
| **Drinks** | Fresh juice, Soft drink, Bottled water |

Each item is shown on its own line with the price at the right, and a **Book a table** button sits at the bottom of the page.

### 3.5 Contact page (`contact.html`)
Lets visitors reserve a table or reach the restaurant directly.

- **Heading:** "Contact and reservations", with a note that the restaurant replies within 30 minutes during opening hours
- **Book a table form** with these fields: Full name, Phone number, Date, Time, Number of guests, and a **Confirm booking** button
- **Find us:** a map or photo showing the location
- **Contact details:** phone and WhatsApp number, email address, opening days and hours (Monday to Sunday), and the address: 12 Wilkinson Road, Freetown

## 4. Features shared by all pages

- The same **header** on every page: the restaurant name on the left and the links Home, About, Services, Menu and Contact on the right, with the current page highlighted
- The same **footer** on every page: the address, phone number and copyright
- A **warm colour palette** of browns and orange used everywhere
- A **responsive layout** that adjusts to computers, tablets and phones
- **Cards with rounded corners** for organised, easy-to-scan information
- **No JavaScript.** Every page uses only HTML and CSS

## 5. Technologies used

| Technology | What it is used for |
| --- | --- |
| **HTML5** | The structure and content of the pages: headings, paragraphs, images, links and the booking form |
| **CSS3** | All styling: colours, spacing, fonts, layout and responsiveness |
| **Flexbox** | Lining up items in a row, such as the header and footer |
| **CSS Grid** | Multi-column layouts, such as the "At a glance" cards |
| **CSS variables** | Storing the colour palette in one place |
| **Google Fonts (Lato)** | The font used across the whole site |

## 6. Project structure

```
PARADISE_TASTE/
├── index.html
├── about.html
├── services.html
├── menu.html
├── contact.html
├── images/
│   ├── restaurant-interior.jpg
│   ├── restaurant-front.jpg
│   ├── seating-area.jpg
│   ├── members.jpg
│   └── menu-items.jpg
└── README.md
```

| File or folder | What it does |
| --- | --- |
| `index.html` | The Home page |
| `about.html` | The About page |
| `services.html` | The Services page |
| `menu.html` | The Menu page |
| `contact.html` | The Contact page |
| `images/` | All the photos used on the site |
| `README.md` | This file, which explains the project |

## 7. How the code works

### 7.1 HTML structure
Every page is built from the same standard sections:

- `<header>` holds the logo and the navigation (`<nav>`)
- `<main>` holds the content that is different on each page
- `<footer>` holds the address, phone number and copyright

### 7.2 CSS variables
The colours are stored once at the top of the CSS, in `:root`:

```css
:root {
  --brown: #7b2d12;
  --brown-light: #9a3412;
  --accent: #c2610f;
  --cream: #fbe9d0;
  --bg: #faf9f7;
  --text: #1c1917;
  --muted: #44403c;
  --border: #e7e5e4;
}
```

Each colour is then used by name, for example `background: var(--brown);`. To change a colour across a page, you change it in one place.

### 7.3 Navigation
The header uses Flexbox to put the logo on the left and the links on the right. The link for the page you are on has the class `.active`, which gives it a lighter brown background. Links also change colour when you hover over them. Every link points to its page file, such as `href="about.html"`.

### 7.4 Cards
Information is shown in white cards with a soft border and rounded corners. These cards are used for the services, the facts, the values and the menu sections. Grid and Flexbox keep them lined up neatly.

### 7.5 Images
Photos use `object-fit: cover` so they are cropped neatly instead of stretched. Each image has a light grey background, so if a photo is missing, a grey box shows instead of a blank gap. Every image also has an `alt` description for accessibility.

### 7.6 Booking form
The form on the Contact page uses HTML form fields: text boxes for name and phone, a date picker, a time picker and a number box for guests. It has no JavaScript, so it shows the layout and fields, but the booking is not sent anywhere yet. Sending bookings would need a back-end or an email service.

### 7.7 Responsive design
Each page has a media query for screens 800 pixels wide or smaller (phones and small tablets):

```css
@media (max-width: 800px) { ... }
```

On small screens the header stacks the logo above the links, two-column layouts become one column, images become shorter and spacing is reduced.

## 8. Design choices

- **Colours:** Dark brown and orange feel warm and connect to food and home-style cooking. Cream text on the brown header is easy to read.
- **Font:** Lato is clean and friendly, and its heavy weight works well for headings and numbers.
- **Cards:** White cards on a light background keep information organised and easy to scan.
- **Consistency:** The same header, footer, colours and card style on every page make the site feel like one brand.
- **Clear actions:** "Reserve a table", "See menu and prices" and "Book a table" buttons guide visitors to the most useful pages.
- **Wireframe match:** The pages follow the wireframes created in Figma.

## 9. How to run the project

1. **Download or clone the repository:**
   ```bash
   git clone https://github.com/bundukajoshua9-source/PARADISE-TASTE.git
   ```
2. **Open the project folder** in VS Code or any file explorer.
3. **Open `index.html`** by double-clicking it. It opens in your default web browser, and you can use the navigation links to visit the other pages.

**Notes:**
- An internet connection is needed to load the Lato font from Google Fonts. Without it, the pages use a default system font.
- The `images` folder must stay in the same folder as the HTML files, or the photos will not appear.

## 10. How to edit the pages

| I want to change... | What to do |
| --- | --- |
| Text on a page | Edit the words between the HTML tags in that page's file |
| A photo | Replace the file in `images/`, keeping the same file name |
| The colours | Change the values in the `:root` section at the top of the CSS |
| A price | Edit the price next to the dish in `menu.html` |
| Phone number or address | Edit the text in the `<footer>` and in `contact.html` |
| The opening hours | Edit them on the Home and Contact pages |

Save the file and refresh the browser to see your changes.

## 11. How to upload changes to GitHub

After you make changes, run these commands in the VS Code terminal:

```bash
git add .
git commit -m "Describe what you changed"
git push
```

- `git add .` prepares all your changed files
- `git commit` saves the changes with a short message
- `git push` uploads them to GitHub

## 12. Possible future improvements

- Make the booking form send reservations to the restaurant by email or a back-end
- Add a mobile menu button for small screens
- Compress the photos so the pages load faster
- Move the CSS into its own file so all five pages share it
- Add a real map to the Contact page

## 13. Author

**Joshua**
Software Engineering student
Limkokwing University of Creative Technology, Sierra Leone

&copy; 2026 Paradise Taste
