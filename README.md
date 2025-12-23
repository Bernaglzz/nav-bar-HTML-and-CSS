# 🛍️ Product Card Component

This project is a stylish and responsive **product card** built with HTML and CSS. It's designed to showcase tech products—like wireless headphones—in a clean, modern layout suitable for e-commerce websites, portfolios, or UI/UX demos.

## 🎯 Project Purpose

The goal of this component is to present a product attractively and clearly, highlighting key details such as pricing, discounts, ratings, and a call-to-action button. It can be easily integrated into larger web projects or used as a standalone feature.

## 🧩 Features

- **Modern Design**: Rounded corners, shadows, and hover effects for a polished look.
- **Discount Badge**: Highlights promotional offers with a floating badge.
- **Price Display**: Shows both original and discounted prices with clear styling.
- **Rating System**: Star-based rating with review count.
- **Add to Cart Button**: Prominent and interactive button to encourage user action.
- **Responsive Layout**: Uses Flexbox for vertical and horizontal centering.

## 🖼️ Visual Preview

Here’s how the product card looks in action:

![Showcase 1](showcase1.png)

![Showcase 1](showcase2.png)

## 🛠️ Technologies Used

- **HTML5**: Semantic structure and accessibility.
- **CSS3**: Styling, transitions, and layout control.
- **Flexbox**: For centering and alignment.
- **Custom Fonts**: Clean and readable typography.

## 📁 File Structure

- `index.html`: Contains the markup for the product card.
- `stylesheet.css`: Holds all styling rules.
- `Headphones.jpg`: Product image used in the card.

## 🧪 How to Use

1. Clone or download the repository.
2. Replace the product image with your own in the `/Image/` folder.
3. Update product details in `index.html`.
4. Customize styles in `stylesheet.css` to match your brand.

## ⚠️ Notes

There is a small CSS typo in the hover effect:
```css
.productcard:hover {
    transform: (1.1); /* Incorrect */
}
