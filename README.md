
# Blackjack: $1K to $100K Challenge

A Java Blackjack game where players start with $1,000 in chips and attempt to reach $100,000 using strategy, betting, and card counting.

## The Problem

Blackjack combines luck, probability, and decision-making. I wanted to create a Blackjack game that goes beyond basic gameplay by introducing difficulty settings, card counting, and strategy recommendations. This project provides a challenge where players can test their Blackjack knowledge, manage their chips, and track their progress toward a $100,000 goal.

## How It Works

Players start with $1,000 in chips and attempt to reach $100,000 by playing Blackjack. Before each round, players place bets and then choose actions such as hitting or standing.

The game will include three difficulty settings:

- **Easy:** Unlimited strategy hints and card-count reveals
- **Normal:** 10 strategy hints and 10 card-count reveals per run
- **Hard:** No strategy hints or card-count reveals, with additional card-count audits

Other planned features include:

- A six-deck card shoe with automatic reshuffling
- A Hi-Lo card-counting system
- A strategy hint system that recommends the best move
- A betting and chip management system
- An end-of-run statistics dashboard
- A line graph showing chip balance changes throughout the game

### System Diagram

![Blackjack System Diagram](BlackJack%20(2).drawio)

## Tech Stack

- **Language:** Java
- **GUI:** Java Swing
- **Graphics:** Java AWT and Graphics2D
- **Libraries:** Java standard libraries, including `ArrayList` and `Collections`
- **Development Environment:** IntelliJ IDEA
- **Version Control:** Git and GitHub

No external APIs or paid libraries are required.

## Setup

### Requirements

- Java Development Kit (JDK)
- IntelliJ IDEA or another Java IDE
- Git

### Installation

Clone the repository:

```bash
git clone https://github.com/DistinguishedToast/Blackjack.git
cd Blackjack
```

Open the project in IntelliJ IDEA.

The project is currently in development, so the game may not be runnable yet.

## Usage

Once implemented, the game will follow this general process:

1. Launch the application
2. Select a difficulty
3. Start with $1,000 in chips
4. Place a bet
5. Play Blackjack by hitting or standing
6. Use strategy hints and card-count reveals if allowed by the selected difficulty
7. Continue playing until reaching $100,000 or losing all chips
8. View the final statistics and balance history

## Roadmap

- [ ] Create the card and deck classes
- [ ] Implement core Blackjack gameplay
- [ ] Add player and dealer actions
- [ ] Implement betting and chip management
- [ ] Add difficulty settings
- [ ] Implement the Hi-Lo card-counting system
- [ ] Implement strategy recommendations
- [ ] Create the Java Swing graphical interface
- [ ] Add card-count audits
- [ ] Create the end-of-run statistics dashboard
- [ ] Add a line graph for chip balance history
- [ ] Test and polish the complete game

## Author

James Monroe

[GitHub](https://github.com/DistinguishedToast)
