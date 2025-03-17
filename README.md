# React State Management Demo

This project demonstrates fundamental React hooks:
- useState for state management
- useEffect for side effects and lifecycle

## Key Features

- Two independent counters using useState
- useEffect with:
  - Empty dependency array (mount/unmount)
  - Specific dependency (count changes)
  - Cleanup functions
- Component lifecycle logging

## Getting Started

1. Clone this repository
2. Install dependencies:
```bash
npm install
```
3. Run the development server:
```bash
npm run dev
```

## What You'll Learn

1. How to manage multiple state variables
2. When useEffect runs based on dependencies
3. Proper cleanup of effects
4. Component lifecycle patterns
5. Passing state as props

## Best Practices

- Separate unrelated state into multiple variables
- Always clean up effects to prevent memory leaks
- Use dependency arrays properly
- Keep effects focused on single purposes

## Technologies Used

- React 18+
- Vite
- Modern JavaScript (ES6+)

## License

MIT
