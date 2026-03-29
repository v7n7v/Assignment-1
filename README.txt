TurtleBot3 Maze Navigation
==========================

Alula Gebreegziabher
CS 485 - AI, NJIT, Spring 2026
Assignment 1: Getting Started with ROS

Setup
-----
Make sure you have Docker installed.

Build:
  docker compose build

Run:
  docker compose up simulation

This launches Gazebo with the TurtleBot3 Burger in the maze world.

Notes
-----
- Uses ROS 2 Humble
- Runs on Docker (works on Mac, Linux, Windows with WSL2)
- The simulation container runs Gazebo Classic with the DRL stage 4 world
- Environment variables can be changed in the .env file
