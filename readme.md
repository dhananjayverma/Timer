# Stopwatch App

This is a simple stopwatch application built using React. It allows users to start, pause, and reset the timer.

## deploy link : <a href="">click here </a>


### StopwatchApp

This component represents the main stopwatch application. It utilizes React hooks for state management.

#### State

- `time`: Represents the current time in seconds.
- `isRunning`: Indicates whether the stopwatch is currently running or paused.

#### Ref

- `intervalRef`: Keeps a reference to the interval used for updating the time.

#### Methods

- `formatTime`: Formats the time in seconds into a human-readable format (HH:MM:SS).
- `startTimer`: Starts the stopwatch by incrementing the time every second using `setInterval`.
- `pauseTimer`: Pauses the stopwatch by clearing the interval.
- `resetTimer`: Resets the stopwatch by setting the time back to 0 and pausing it.

#### Render

- Renders the stopwatch UI, including the time display and control buttons.

## Usage

To use this stopwatch in your project:

1. Import the `StopwatchApp` component.
2. Include it in your JSX markup.
3. Customize styles by modifying the `Stopwatch.css` file.

### Example

```jsx
import React from "react";
import StopwatchApp from "./StopwatchApp";

function App() {
  return (
    <div className="App">
      <StopwatchApp />
    </div>
  );
}

export default App;
```

# How to Run
## To run the application locally:

Clone this repository.
Install dependencies using npm install.
Run the development server using npm start