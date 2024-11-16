# 🍲 MealWise: Meal Planner & Grocery List
> Plan weekly meals and automatically generate a shopping list. Integrate with recipes and nutrition information for a seamless meal-planning experience.

## 📋 Project Scale: Medium-High
Expected timeline: 4-6 weeks

## 🎯 Core Purpose
MealWise helps users create a weekly meal plan and generate a grocery list based on selected recipes. With integration to recipe APIs and nutrition databases, users can manage meals and maintain a balanced diet effortlessly.

## ⚡ Features Breakdown

### Phase 1: Core Meal Planning Functionality
- [ ] **Recipe Search and Selection**: Allow users to search for recipes from an external API (e.g., Spoonacular) and add them to their meal plan.
- [ ] **Weekly Meal Calendar**: Display a weekly view where users can assign meals to each day, for breakfast, lunch, and dinner.
- [ ] **Shopping List Generation**: Automatically compile a shopping list from the ingredients of selected recipes.

### Phase 2: Enhancing Meal and Ingredient Management
- [ ] **Nutrition Information**: Display nutrition information for each meal using an API like Spoonacular or Edamam.
- [ ] **Ingredient Consolidation**: Group ingredients in the shopping list by type (e.g., all dairy products together) and consolidate quantities (e.g., 2 cups + 1 cup of flour = 3 cups).
- [ ] **Editable Shopping List**: Allow users to add, remove, or modify items in the generated grocery list.

### Phase 3: Advanced Features
- [ ] **Recipe Favorites and History**: Let users save favorite recipes and view past meal plans.
- [ ] **Diet and Allergy Filters**: Enable filters for dietary preferences (e.g., vegan, gluten-free) and allergens.
- [ ] **Custom Recipes**: Allow users to manually add custom recipes to the meal planner.
- [ ] **Print or Export Grocery List**: Option to print or export the grocery list as a PDF.

## 🛠️ Key Libraries & Tools
- **Axios or Fetch API**: For API calls to retrieve recipes and nutrition data.
- **React Calendar**: To create the weekly meal calendar.
- **React Context or Redux**: For managing state across the meal planner and shopping list.
- **localForage**: For saving user data offline (e.g., favorites or past meal plans).

## 📚 Implementation Resources
- [ ] **Spoonacular API Documentation**: [Spoonacular API](https://spoonacular.com/food-api)
- [ ] **Edamam Nutrition API**: [Edamam API](https://developer.edamam.com/)
- [ ] **React Calendar Library**: [React Calendar](https://github.com/wojtekmaj/react-calendar)
- [ ] **Redux Docs**: [Redux Documentation](https://redux.js.org/)

## 💡 Example Apps
• **Mealime**: A meal planner app with integrated recipes and shopping lists.
• **Yummly**: Allows users to search and save recipes, with options to filter by dietary preferences.