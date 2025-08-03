# NFA Simulation - Futuristic Neon

## Project Overview

 The **NFA Simulation - Futuristic Neon** is a **web-based tool** designed to simulate and visualize the behavior of a **Non-deterministic Finite Automaton (NFA)**. This tool allows users to define states, transitions, start state, and accepting states for an NFA. The project offers an interactive interface where users can simulate how the automaton processes input strings and visualize its behavior in real-time.

---

## Features

- **Define NFA Configuration**: Easily input states, start state, accepting states, and transitions.
- **Interactive Visualization**: View the automaton's states and transitions as they are processed.
- **Real-Time Simulation**: Enter an input string and simulate the NFA's response to it.
- **Responsive Design**: The simulation tool works seamlessly on both desktop and mobile devices.

---

## How to Use

1. **Input NFA Details**:

   - **States**: Enter the states of the NFA (comma-separated, e.g., `q0,q1,q2`).
   - **Start State**: Define the start state (e.g., `q0`).
   - **Accepting States**: Enter the accepting states (comma-separated, e.g., `q2`).
   - **Transitions**: Input transitions in the format: `fromState symbol toStates` (e.g., `q0 a q1,q2`).

2. **Create NFA**: Click the **Create NFA** button to generate the automaton.

3. **Simulate Input**: Enter a string and click **Start Simulation** to watch the NFA process the input.

4. **Result**: The tool will display whether the string is **Accepted** or **Rejected**, based on whether the automaton reaches an accepting state.

---

## Technologies Used

- **HTML5**: Structure and layout of the web page.
- **CSS3**: Styling for the user interface, with a futuristic neon theme.
- **JavaScript**: Implements the logic for simulating NFA behavior, handling state transitions, and rendering on the canvas.
- **Canvas API**: Used to render the NFA states and transitions visually.

---

## Output Example

- After entering a string, the tool will animate the NFA's state transitions.
- The simulation will step through the string, processing each symbol.
- The final result will display either **Accepted** or **Rejected**, depending on the automaton's behavior.

---

## How to Run the Project

1. **Clone the repository**:

   ```bash
   git clone https://github.com/gotamk-786/NFA Simulation - Futuristic Neon.git

   ```

2. Open the index.html file in your browser to run the simulation.

## Contributing

If you would like to contribute to this project, feel free to fork the repository, make changes, and submit a pull request. Contributions are welcome!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- This project was developed as part of a **4th-semester Automata Theory project**.
- Thanks to **MDN Canvas API documentation** for helping with the visualization part of the project.MDN.
