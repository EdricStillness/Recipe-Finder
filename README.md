# Recipe Finder

A beautiful, modern web application for finding delicious recipes using TheMealDB API. Built with vanilla HTML, CSS, and JavaScript with stunning 3D glassmorphism design.

 **Live Demo**: [https://tranmaitiendat.github.io/Recipe-Finder/](https://tranmaitiendat.github.io/Recipe-Finder/)

##  Features

### Smart Search Options
- **Search by Name**: Find recipes by dish name
- **Search by Ingredient**: Find recipes containing specific ingredients (supports multiple ingredients)
- **Search by Category**: Browse recipes by category (Dessert, Seafood, Vegetarian, etc.)
- **Search by Area**: Explore cuisines from different regions (Italian, Japanese, Vietnamese, etc.)

###  Random Recipe Generator
- Get random recipe suggestions
- Smart random based on selected filters (category/area)
- Perfect for when you don't know what to cook!

###  Modern UI/UX
- **3D Glassmorphism Design**: Beautiful translucent cards with blur effects
- **Responsive Grid Layout**: 1-4 columns based on screen size
- **Smooth Animations**: Hover effects and floating animations
- **Mobile Friendly**: Fully responsive design

###  Advanced Features
- **Modal Recipe Details**: View full recipes with ingredients and instructions
- **Real-time API Integration**: Live data from TheMealDB
- **Multi-ingredient Search**: Search with multiple ingredients (fallback for free API)
- **YouTube Integration**: Direct links to recipe videos when available

##  Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/TranMaiTienDat/Recipe-Finder.git
   cd Recipe-Finder
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your web browser
   open index.html
   # or
   start index.html
   ```

3. **Or visit the live demo**: [https://tranmaitiendat.github.io/Recipe-Finder/](https://tranmaitiendat.github.io/Recipe-Finder/)

4. **Start cooking!** 

## 📁 Project Structure

```
Recipe Finder/
├── index.html          # Main HTML file
├── style.css           # 3D styling and animations
└── README.md          # Project documentation
```

## Design Features

### 3D Background
- Animated gradient background with floating effects
- Glassmorphism container with backdrop blur
- Multi-layered shadows for depth

### Interactive Elements
- Hover animations on recipe cards
- Transform effects on buttons
- Smooth transitions throughout

### Color Scheme
- Primary: Gradient green (#4CAF50 to #45a049)
- Background: Purple-blue gradient (#667eea to #764ba2)
- Accent: Orange-blue gradient for action buttons

## API Integration

This project uses the free [TheMealDB API](https://www.themealdb.com/api.php):

- **Search by name**: `search.php?s={name}`
- **Filter by ingredient**: `filter.php?i={ingredient}`
- **Filter by category**: `filter.php?c={category}`
- **Filter by area**: `filter.php?a={area}`
- **Random recipe**: `random.php`
- **Recipe details**: `lookup.php?i={id}`

##  Responsive Design

- **Mobile** (< 600px): 1 column layout
- **Tablet** (600px - 900px): 2 columns
- **Desktop** (900px - 1200px): 3 columns
- **Large Desktop** (> 1200px): 4 columns

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Advanced styling with glassmorphism effects
- **Vanilla JavaScript**: ES6+ with async/await
- **TheMealDB API**: Recipe data source
- **Responsive Design**: Mobile-first approach

##  Screenshots

### Main Interface
![Main Interface](screenshots/main-interface.png)

### Recipe Modal
![Recipe Modal](screenshots/recipe-modal.png)

### Filter Options
![Filter Options](screenshots/filter-options.png)

##  Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

##  License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

##  Acknowledgments

- [TheMealDB](https://www.themealdb.com/) for providing the free recipe API
- Design inspiration from modern glassmorphism trends
- Icons and emojis for enhanced user experience

##  Future Enhancements

- [ ] Save favorite recipes to localStorage
- [ ] Recipe rating system
- [ ] Shopping list generator
- [ ] Offline mode with cached recipes
- [ ] Dark/Light theme toggle
- [ ] Advanced filtering (prep time, difficulty)
- [ ] Recipe sharing functionality

---


