# Arabic-Mock-data

Reusable, Arabic-friendly mock datasets for UI prototyping, API simulations, and frontend testing.

![Design Thumbnail](https://res.cloudinary.com/dcvfwtpdo/image/upload/v1763929603/thumbnail_sqkl2f.png)

---

## Overview

A comprehensive collection of Arabic mock data covering various domains including ecommerce, users, real estate, cars, recipes, reviews, and more. All data is structured in JSON format with Arabic content, making it perfect for building Arabic-language applications and prototypes.

## Features

- **Arabic Content**: All text, descriptions, and data are in Arabic
- **Structured JSON**: Clean, consistent JSON format across all datasets
- **Cloudinary Images**: High-quality images hosted on Cloudinary
- **Comprehensive Coverage**: 12+ data categories with thousands of records
- **Consistent Format**: Follows strict guidelines for IDs, naming, and structure

## Dataset Categories

1. **Ecommerce** - Products across multiple categories (electronics, clothes, food, etc.)
2. **Users** - User profiles with avatars and social links
3. **Companies** - Company information and details
4. **Cars** - Vehicle listings with specifications
5. **Orders** - Order and order item data
6. **Reviews** - User, product, and company reviews
7. **Real Estate** - Properties and agent listings
8. **Recipes** - Arabic recipes with ingredients and instructions
9. **Misc** - FAQs, tips, and other miscellaneous data

## Project Structure

```
data/
  ├── cars/
  │   └── cars.json
  ├── users/
  │   └── users.json
  ├── real-estate/
  │   ├── agents.json
  │   ├── properties.json
  │   └── locations.json
  ├── recipes/
  │   ├── recipes.json
  │   └── ingredients.json
  ├── reviews/
  │   ├── user-reviews.json
  │   ├── product-reviews.json
  │   └── company-reviews.json
  ├── orders/
  │   ├── orders.json
  │   └── order-items.json
  └── misc/
      ├── faq.json
      └── tips.json

assets/
  ├── cars/
  │   └── images-guide.txt
  ├── avatars/
  │   └── images-guide.txt
  └── real-estate/
      ├── agents/
      │   └── images-guide.txt
      └── properties/
          └── images-guide.txt
```

## Usage

### Direct JSON Access

You can access the JSON files directly from the repository:

```javascript
// Example: Fetch cars data
fetch('https://raw.githubusercontent.com/USERNAME/Arabic-Mock-data/main/data/cars/cars.json')
  .then(response => response.json())
  .then(data => console.log(data));
```

### Image URLs

All images are hosted on Cloudinary and can be accessed directly:

- **Cars**: 30 car images (car-001 through car-030)
- **Users**: 100 user avatars (user-001 through user-100)
- **Real Estate Agents**: 20 agent portraits (using user avatars)
- **Real Estate Properties**: Multiple images per property listing

## Data Guidelines

This project follows strict guidelines to ensure consistency:

- **ID Format**: All IDs use string format with zero-padding (e.g., `"car-001"`, `"user-050"`)
- **Image URLs**: All images use Cloudinary URLs in WebP format
- **JSON Structure**: Arrays of objects with consistent field names
- **Naming**: Lowercase with hyphens for files and camelCase for JSON keys

For detailed guidelines, see:
- [DATA_GUIDELINES.md](./DATA_GUIDELINES.md) - Data structure and format rules
- [IMAGES_GUIDELINES.md](./IMAGES_GUIDELINES.md) - Image asset organization

## Statistics

- **Cars**: 30 listings
- **Users**: 100 profiles
- **Real Estate Agents**: 20 agents
- **Real Estate Properties**: 60+ properties
- **Recipes**: 30 recipes
- **Reviews**: 45+ reviews across categories

## Contributing

When contributing to this project:

1. Follow the guidelines in `DATA_GUIDELINES.md` and `IMAGES_GUIDELINES.md`
2. Ensure all IDs follow the string format pattern
3. Use Cloudinary for all image hosting
4. Maintain Arabic content quality
5. Keep JSON structure consistent

## License

[Add your license information here]

---

**Note**: This is a mock data repository designed for development and prototyping purposes.