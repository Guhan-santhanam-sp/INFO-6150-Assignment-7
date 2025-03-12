### INFO-6150-Assignment-7

## 1. Variables
- Defined variables for colors, fonts, and spacing to maintain consistency across the website.

- Example: $primary-color, $font-family, $spacing.

## 2. Custom Properties
- Integrated CSS custom properties alongside SASS variables for dynamic styling.

- Example: --primary-color used in conjunction with $primary-color.

## 3. Nesting
- Used nesting to organize styles hierarchically, improving code readability and structure.

- Example: .navbar { ... .nav-item { ... } }.
## 4. Components

- Navbar: Uses Flexbox layout (@use 'layout/flexbox';) and variables like $primary-color for background color.

- Why Choose Us Section: Employs Flexbox for layout and variables like $primary-color for text color.

- Testimonials Section: Uses CSS Grid with variables like $spacing for grid gaps.

- Product Cards: Apply variables like $spacing for padding and $primary-color for hover effects.