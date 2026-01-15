# SchoolProject — School Cleanup Map

## Project overview

SchoolProject is a lightweight web application designed to help schools and local communities keep their city cleaner. Users can mark and share public locations where litter has been collected, helping volunteers and students coordinate cleanup efforts.

Key ideas:
- Map public litter-collection points.
- Allow registered users to add new points.
- Let users confirm they cleaned a location by "liking" a point.

## Features
- Interactive map showing marked cleanup points.
- Add new points with a short description or photo.
- User accounts: register and sign in to contribute and track activity.
- Likes / confirmations to show which points have been cleaned most recently.
- Basic user statistics and history.

## Tech stack
- Frontend: HTML, CSS, JavaScript (can integrate React or another modern framework)
- Backend: Node.js with Express
- Database: MongoDB or PostgreSQL
- Maps: Google Maps API or OpenStreetMap

## Quick start

1. Clone the repository:
```bash
git clone https://github.com/Ivan22032009/SchoolProject.git
```

2. Change into the project directory:
```bash
cd SchoolProject
```

3. Install dependencies:
```bash
npm install
```

4. Set required environment variables (example):
```bash
export NODE_ENV=development
export MONGODB_URI="your-database-uri"
export MAPS_API_KEY="your-google-maps-api-key"
```

5. Start the app:
```bash
npm start
```

Open http://localhost:3000 (or the port configured in your app) in your browser.

## Contributing
We welcome contributions! Ways to help:
- Open Issues to suggest new features or report bugs.
- Send Pull Requests with improvements or fixes.
- Improve documentation, translations, and accessibility.

When contributing, please:
- Create a clear PR description.
- Keep changes small and focused.
- Run and test locally before submitting.

## Notes
- The original README content was in Ukrainian and has been translated and improved.
- This project is intended as a lightweight school/community tool; feel free to adapt the stack and deployment to your needs.

## Thank you
Thanks for supporting cleaner communities — together we can make our city cleaner and safer!
