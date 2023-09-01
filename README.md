# Minimax Furious Hunter Dracula

![Minimax-Furious-Hunter-Dracula](repository-banner.png)

## Welcome to the Future of Heuristic Gaming!

[![GitHub issues](https://img.shields.io/github/issues/your-username/Minimax-Furious-Hunter-Dracula)](https://github.com/your-username/Minimax-Furious-Hunter-Dracula/issues)
[![GitHub forks](https://img.shields.io/github/forks/your-username/Minimax-Furious-Hunter-Dracula)](https://github.com/your-username/Minimax-Furious-Hunter-Dracula/network)
[![GitHub stars](https://img.shields.io/github/stars/your-username/Minimax-Furious-Hunter-Dracula)](https://github.com/your-username/Minimax-Furious-Hunter-Dracula/stargazers)
[![GitHub license](https://img.shields.io/github/license/your-username/Minimax-Furious-Hunter-Dracula)](https://github.com/your-username/Minimax-Furious-Hunter-Dracula/blob/main/LICENSE)

Welcome to **Minimax Furious Hunter Dracula**, an AI-based Heuristic game based on graph algorithms, played by predicting the next move of the hunter by Dracula, all implemented in C. Are you ready to delve into the world of C-based game development, where you play as Dracula, predicting the next move of the hunter based on their previous set of visible moves? Brace yourself for an unparalleled gaming experience!

## Summary 

An AI based Heuristic game based on graph algorithms, which is played by predicting the next move of hunter by dracula based on the previous set of hunter's visible moves. We use basic Dijkstra's and breadth first search for the purpose of this project with a slight variation of minimax algorithm to predict the next move.

## What Is Minimax Furious Hunter Dracula?

Minimax Furious Hunter Dracula is a one-of-a-kind game that combines C programming, strategy, graph algorithms, and artificial intelligence. In this game, you take on the role of Dracula, a cunning and elusive character. Your objective is to outwit the hunters by predicting their next move based on the information available.

### Key Features

- **C Programming**: Dive deep into C programming as you explore the codebase and contribute to this exciting project.

- **Graph Algorithms**: We leverage the power of graph algorithms, including Dijkstra's and breadth-first search, implemented in C, to create an immersive gaming experience.

- **AI-Powered Gameplay**: Dracula's moves are driven by a modified Minimax algorithm, all implemented in C, making the gameplay challenging and exciting.

- **Sticker Customization**: Personalize your in-game experience with a wide range of stickers and customizations.

- **Real-Time Leaderboards**: Compete with players from around the world and climb the ranks on our real-time leaderboards.

- **GitHub Integration**: Collaborate with fellow gamers, report issues, and contribute to the C codebase through GitHub.

### Gameplay Mechanics

In Minimax Furious Hunter Dracula, players are faced with strategic decisions:

- As Dracula, use your wits and AI-driven predictions, implemented in C, to evade the hunters.
- As a hunter, coordinate with your team to track down Dracula and prevent their escape.

### Code Highlights

#### Dracula AI (dracula.c)

```c
// This code defines Dracula's decision-making process in the game.
// It takes into account hunter movements, location analysis, and
// strategic decision-making.

// Some key functions include:
// - findDistancetoallCities: Calculates distances from Dracula's
//   location to all cities using graph traversal.
// - ShortestPathforClosestHunter: Finds the shortest path from
//   Dracula's current location to a strategically picked location.

void decideDraculaMove(DraculaView dv) {
    // Your Dracula AI code here
    // ...
}
```

## Hunter AI (hunter.c)

```c
// This code defines the decision-making process for the hunters in
// the game. It considers factors like Dracula's movements and
// health status.

// Key functions include:
// - decideHunterMove: Determines the hunter's next move based on
//   various conditions, including the game round and Dracula's
//   location.

void decideHunterMove(HunterView hv) {
    // Your Hunter AI code here
    // ...
}
```

## Examples

## Dracula AI Example

```c
// If Dracula is on the first turn, analyze hunter movements and
// choose a location far away and not easily reachable by hunters.

// Randomly select a location based on specific criteria.
if (Curr_Location == NOWHERE) {
    // Your logic here
    // ...
}
```

## Hunter AI Example

```c
// If the hunter is dead, send them to the hospital.

if (HvGetHealth(hv, curr_player) <= 0) {
    // Send the hunter to the hospital
    strcpy(city, placeIdToAbbrev(HOSPITAL_PLACE));
}
```

## Installation and Getting Started

1. Clone this repository to your local machine.
2. Compile and run the C code following the instructions in the Installation Guide.
3. Launch the game and start playing as Dracula or a hunter.

For more detailed instructions and strategies, please refer to our Wiki.

## Contributing

We welcome contributions from the C programming community to make Minimax Furious Hunter Dracula even more exciting. If you have ideas for improvements, bug fixes, or new features, please check our Contributing Guidelines.

## Development Roadmap

Our development roadmap includes exciting features like:

1. Multiplayer support
2. Advanced AI strategies
3. Enhanced graphics and animations, all implemented in C.

Your contributions can help us reach these milestones faster!

1. Get Started
2. Download the Latest Release
3. Read the Documentation
4. Explore the C Code

## Join the Community

Connect with other C programmers, players, and developers in our community spaces:

Discord

Forums

## License

This project is licensed under the MIT License - see the LICENSE file for details.

Get ready to embark on a thrilling journey with Minimax Furious Hunter Dracula in C. Don't just play games; craft your destiny. Join us today, contribute to the C codebase, and let the games begin.
