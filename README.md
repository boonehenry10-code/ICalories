# ICalories

ICalories is a student-focused dining menu app for Ithaca College. It displays the current menu for Campus Center and Terrace Dining Hall in one page.

## Run it

Open `index.html` in a browser. The app uses plain HTML, CSS, and JavaScript; there is no build step. Favorite dishes, meal photo check-ins, daily meal plans, the user's optional calorie goal, and reaction preferences are saved in browser localStorage on the current device. On first visit, an optional setup asks whether the user wants to track a goal; it accepts any positive number, with no preset maximum or increment. ICalories does not calculate or recommend calorie targets. When enabled (the default), the dramatic red screen triggers when adding a food first takes the plan over the saved goal and repeats on each later addition that raises the estimate while it remains over. Reaction settings are in **Profile (S) → Reaction preferences**; users can turn the effect off, select “GOAL CHECK!”, choose “FATTY!” or custom wording, and enable or disable speech. The effect can be previewed; speech depends on browser support and device volume. Nutrition feedback is general and based on the user's meal description; it does not identify foods from photos or provide medical advice. Meal plans allow foods from the imported menu or custom entries on any selected date.

## Menu data

The menus in `app.js` were transcribed from Ithaca College Nutrislice for November 2–8, 2026. Use the date selector under each dining hall heading to switch among the available menus. Campus Center has menu entries through Saturday, November 7; Terrace has entries through Friday, November 6. No menus were posted for Terrace on November 7 or either hall on Sunday, November 8. Dish availability can change. Nutrislice item-level calorie values were not available in the inspected details. The app now shows rough per-serving calorie and macro estimates based on common food profiles and typical portions, informed by USDA FoodData Central. Carbohydrate, sugar, total fat, trans fat, and unsaturated fat values are modeled estimates, not official IC Dining values; customizable stations display “Varies.” Recipe, portion, topping, and preparation differences can change actual values.

## Publish on GitHub Pages

1. Push these files to the `main` branch of the GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. GitHub will show the published URL in the Pages settings.

## Team

Team 4: Anthony A., Boone H., and Jacob M. Add each person's role and contribution here as the project develops.
