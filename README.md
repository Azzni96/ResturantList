# Restaurant List Application
This is a Progressive Web Application (PWA) built with Vite and TypeScript that displays a list of
Finnish student restaurants, allows users to view daily or weekly menus, and provides location
information using Leaflet maps.
## Features
- Restaurant List: View a list of restaurants with their details such as name, company, and address.
- Search Functionality: Filter restaurants based on name, company, or address.
- Daily and Weekly Menus: Toggle between daily and weekly menus of the selected restaurant.
- Dark Mode Toggle: Switch between light and dark themes, with the preference saved in
localStorage.
- Map Integration: Displays restaurant locations on a map using Leaflet and OpenStreetMap.
- User Authentication: Basic sign-up and login functionality with JWT tokens.
- Responsive Design: The application is designed to work on various screen sizes.
## Technology Stack
- Frontend:
 - TypeScript
 - HTML5
 - CSS3
 - Leaflet.js for map integration
 - Vite for project setup and development
- Backend (External API):
 - Fetches data from Metropolia's Restaurant API
## Installation
To run the project locally:
1. Clone the repository:
`` git clone https://github.com/your-repository-url.git``
2. Navigate to the project directory:
 ``cd your-project-directory``
3. Install dependencies:
 ``npm install``

4. Install Vite PWA:
  `` npm install vite-plugin-pwa``

5. Install Leaflet for maps:
  `` npm install leaflet``

6. Run the development server:
 ``npm run dev``

7. Build the project for production:
 ``npm run build``

The production-ready files will be in the dist/ directory.
PWA Configuration
This project is a fully functional Progressive Web Application (PWA). It can be installed on devices, and it includes:

Offline support: Uses service workers to cache necessary assets, allowing offline access.
Auto updates: Automatically updates when new versions are available.
App manifest: Configures the app name, icons, and theme for installation.
## API Endpoints
- GET /api/v1/restaurants: Fetches the list of restaurants.
- GET /api/v1/restaurants/daily/{id}/fi: Fetches the daily menu of a restaurant.
- GET /api/v1/restaurants/weekly/{id}/fi: Fetches the weekly menu of a restaurant.
## Usage
- Sign Up / Login: Users can sign up or log in to the application. Once logged in, their session is
stored using JWT tokens.
- Search: You can search for restaurants by name, company, or address using the search bar at the
top of the page.
- View Menus: After clicking on a restaurant, a modal will open showing the daily menu by default.
You can switch to the weekly menu by using the "Day Menu" or "Week Menu" buttons.
- Dark Mode: Use the sun/moon icon at the top of the page to toggle between light and dark themes.
## File Structure
The project follows a structured file layout:
src/
 components.ts
 Fetchdata.ts
 sginapi.ts
 RavintolaLista.ts
 variables.ts
public/
 main.css
index.html
## How to Contribute
Contributions are welcome! If you find a bug or want to suggest an improvement, feel free to open
an issue or submit a pull request.
## License
This project is licensed under the MIT License.
