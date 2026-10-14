# student-mobile-portal
A student portal project for practicing Git and GitHub collaboration.

## Components

### StudentProfile

`StudentProfile.jsx` is a reusable React component that displays a student's basic information:

- Name
- Student ID
- Program

It uses fictional sample data only. No real student records are stored in this repository.

## Using StudentProfile

This standalone exercise does not include a full React app yet. When the project is set up as a React app (for example with Vite), place `StudentProfile.jsx` in `src/components/` and render it from a parent component:

```jsx
import StudentProfile from "./components/StudentProfile";

function App() {
  return (
    <main>
      <h1>Student Mobile Portal</h1>
      <StudentProfile />
    </main>
  );
}

export default App;
```
