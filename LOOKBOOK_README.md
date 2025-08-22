# Lookbook Section for Shopify Theme

## Overview

The Lookbook section creates an interactive, shoppable gallery that displays your products in lifestyle photos. Customers can click on "shoppable" hotspots to view product details and add items to their cart directly from the image, creating an engaging, story-driven shopping experience.

## Features

- **Interactive Hotspots**: Clickable points on images that reveal product information
- **Product Quick View**: Modal popup with product details and add-to-cart functionality
- **Hover Tooltips**: Product previews that appear when hovering over hotspots
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Customizable Styling**: Adjust colors, sizes, and animations
- **Shopify Admin Integration**: Easy setup through the theme editor

## How It Works

1. **Lifestyle Images**: Upload high-quality lifestyle photos featuring your products
2. **Product Hotspots**: Place clickable hotspots on specific products in the images
3. **Interactive Shopping**: Customers click hotspots to view product details
4. **Quick Purchase**: Add products to cart directly from the lookbook
5. **Seamless Experience**: Maintains the shopping flow without leaving the page

## Setup Instructions

### 1. Add the Section to Your Page

1. Go to your Shopify admin → Online Store → Themes
2. Click "Customize" on your active theme
3. Navigate to the page where you want to add the lookbook
4. Click "Add section" and search for "Lookbook"
5. Select the Lookbook section to add it to your page

### 2. Configure the Section

#### General Settings
- **Heading**: Main title for your lookbook (e.g., "Spring Collection Lookbook")
- **Subheading**: Descriptive text below the heading
- **Hotspot Size**: Adjust the size of clickable hotspots (15-30px)
- **Hotspot Color**: Choose the color of hotspot dots
- **Hotspot Border Color**: Select the border color for hotspots
- **Hotspot Animation**: Choose between pulse, bounce, or no animation

#### Section Padding
- **Padding Top**: Space above the section
- **Padding Bottom**: Space below the section

### 3. Add Lookbook Images

1. Click "Add block" → "Lookbook Image"
2. Upload your lifestyle image
3. Add a title and description for the image
4. Repeat for additional images

### 4. Create Product Hotspots

1. Click "Add block" → "Product Hotspot"
2. **Attach to Image**: Select which lookbook image this hotspot belongs to
3. **Product**: Choose the product this hotspot represents
4. **Position**: Set horizontal (X) and vertical (Y) position as percentages
5. **Show Tooltip**: Enable/disable hover tooltips

#### Positioning Tips
- **X Position**: 0% = left edge, 100% = right edge
- **Y Position**: 0% = top edge, 100% = bottom edge
- **Recommended**: Keep hotspots between 5-95% to avoid edges

## Customization Options

### Colors and Styling
- Hotspot colors and borders
- Section padding and spacing
- Image overlay text colors
- Modal styling and colors

### Layout
- Grid layout (responsive)
- Image aspect ratios
- Hover effects and animations
- Mobile responsiveness

### Functionality
- Tooltip display options
- Quick add to cart
- Product modal information
- Cart integration

## Best Practices

### Image Selection
- Use high-quality lifestyle photos (1200px+ width recommended)
- Ensure products are clearly visible
- Maintain consistent aspect ratios
- Consider mobile viewing experience

### Hotspot Placement
- Place hotspots directly on products
- Avoid overlapping hotspots
- Test positioning on different screen sizes
- Use descriptive product names

### Content Strategy
- Tell a story with your images
- Group related products together
- Update seasonally with new collections
- Include clear call-to-actions

## Technical Details

### File Structure
```
sections/
  └── lookbook.liquid          # Main section file
templates/
  └── page.lookbook.json       # Sample template
locales/
  └── en.default.json          # Localization strings
```

### Dependencies
- Shopify Online Store 2.0
- Modern browser support (ES6+)
- CSS Grid and Flexbox support

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Troubleshooting

### Common Issues

**Hotspots not appearing**
- Check that hotspots are attached to the correct image
- Verify product selection in hotspot settings
- Ensure image is uploaded and visible

**Modal not opening**
- Check browser console for JavaScript errors
- Verify product data is properly set
- Test with different products

**Styling issues**
- Clear browser cache
- Check for CSS conflicts
- Verify theme compatibility

### Performance Tips
- Optimize image sizes (max 1200px width)
- Limit hotspots per image (recommended: 3-5)
- Use lazy loading for images
- Minimize JavaScript complexity

## Examples

### Fashion Lookbook
- Lifestyle shots in urban settings
- Multiple products per image
- Seasonal collection themes
- Story-driven narratives

### Home & Garden
- Room setup scenarios
- Product combinations
- Lifestyle inspiration
- Before/after transformations

### Food & Beverage
- Recipe presentations
- Ingredient showcases
- Serving suggestions
- Seasonal themes

## Support

For technical support or customization requests:
1. Check the Shopify theme documentation
2. Review browser console for errors
3. Test with different products and images
4. Verify theme compatibility

## Updates

This section is designed to work with Shopify's latest features and will be updated to maintain compatibility with new Shopify releases.

---

**Note**: This lookbook section creates an engaging shopping experience that can significantly increase customer engagement and conversion rates by making the buying process more interactive and inspiring.
