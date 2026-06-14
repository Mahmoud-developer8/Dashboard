Act as an expert UI/UX and Front-End Developer. Write a clean, semantic, and fully responsive HTML5 and CSS3 code for a modern Restaurant Admin Dashboard. 

The design should look professional, clean, and data-driven. Use a light or dark modern tech palette (e.g., slate gray background, white content cards, with vibrant accents like emerald green for success/revenue and orange/red for alerts/orders).

Please provide the code in two separate files: `dashboard.html` and `dashboard.css`.

### Layout Structure & Requirements:
1. **Sidebar Navigation (Left Side):**
   - Fixed on the left (collapsible or responsive on mobile).
   - Restaurant Logo/Name at the top.
   - Menu links with placeholders for icons: Dashboard, Orders, Menu Management, Analytics, Customers, and Settings.
   - Active state styling for the current page.

2. **Main Content Area (Right Side):**
   - **Top Header:** Display the page title ("Dashboard Overview"), a search bar, a notification icon, and an Admin Profile dropdown placeholder.
   
3. **Statistical Cards Section (Top of Main Content):**
   - A responsive 4-column grid displaying key metrics:
     * Card 1: Total Revenue (e.g., $12,450) with a green "+12% today" indicator.
     * Card 2: Active Orders (e.g., 25).
     * Card 3: New Customers (e.g., 180).
     * Card 4: Tables Booked (e.g., 8/15).

4. **Recent Orders & Popular Dishes (Two-Column Layout):**
   - **Left Column (60% width):** A clean, scrollable "Recent Orders" Table. Columns should include: Order ID, Customer Name, Item, Price, and Status (styled with colored badges: Pending, Preparing, Delivered).
   - **Right Column (40% width):** A list of "Popular Dishes" with a thumbnail image placeholder, dish name, number of times ordered, and total sales.

### Technical Guidelines:
- Use semantic HTML5 tags exclusively.
- Use CSS Flexbox and Grid to ensure the dashboard transitions smoothly between desktop, tablet, and mobile screens.
- Use a clean, highly readable font (like 'Inter' or 'Roboto').
- Include modern CSS effects like subtle box-shadows for cards, smooth hover transitions on buttons/links, and clean borders.
- Pure HTML and CSS only—no external frameworks like Bootstrap or Tailwind. Include clear comments in the code.
