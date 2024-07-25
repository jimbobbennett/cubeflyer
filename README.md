# The Flying Cube Game!

A sample JavaScript game that is fiendishly hard. This can be used for some fun demos of [Pieces for Developers](https://pieces.app).

## Pre-requisites

1. Either [VS Code](https://code.visualstudio.com/) or [WebStorm](https://www.jetbrains.com/webstorm/).
1. [Pieces for Developers](https://pieces.app), along with the relevant browser extension.

There are no dependencies to install.

This was tested using Gemini 1.5 as the LLM.

## Run the code

To run the code, open the './game/index.html' file in your browser. Use the space key to start the game and to move the cube up, Gravity brings it back down. Try to avoid the blocks, floor and ceiling.

## Back story

You are a developer picking up this code for the first time. Your first task is to change the cube to something else

## Demo 1 - describe the code

As a new developer on this project, you want a quick overview of the code.

1. Show the game running.
1. Open Pieces desktop
1. Start a new copilot chat
1. Add the [`game`](./game/) folder as context
1. Ask the copilot to explain the code with the prompt 'Describe the cubeflyer project'

## Demo 2 - change the cube to a sphere

You have been asked to change the cube to a sphere. You have no idea how to do this, so you will need to research it.

1. In the same copilot chat, ask the copilot how to change the cube to a sphere with the prompt 'how can I change the cube to be a sphere?'
1. Save the output code snippet to Pieces
1. Show the annotated snippet
1. Open the game in your IDE
1. Find the snippet in your saved materials
1. Add the code to the game
1. Show the game running with the sphere - you will need to refresh the browser

## Demo 3 - make the sphere red

1. In your IDE, select the `init` function
1. Right click, Pieces, ask copilot
1. Ask 'make the sphere red'
1. Add the code into the `init` function
1. Show the game running with the red sphere - you will need to refresh the browser

## Demo 4 - live context

You want to change the lighting in the game.

1. Open [doc.babylonjs.com/features/featuresDeepDive/lights](https://doc.babylonjs.com/features/featuresDeepDive/lights) in your browser and read about lighting
1. Start a new copilot chat with live context
1. Ask the copilot to explain the lighting types with the prompt 'describe the types of lighting in the babylonjs documentation I was just reading'
1. Read about directional lighting
1. Open the `game/src/scene.js` file in your IDE
1. Use the code lens to explain the code
1. Ask the copilot how to use a directional light with the prompt 'How can I change this to use a directional light?'
1. Insert the code and refresh the browser
