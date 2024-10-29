# LinkedIn AI Reply Chrome Extension

## Overview

This project is a Chrome extension created as a take-home assignment for the React Developer role at [ChatGPT Writer](https://chatgptwriter.ai). The extension enhances LinkedIn messaging by providing users with an AI-generated reply feature. This assignment demonstrates my ability to learn new technologies and quickly apply them in a project.

## Objective

The extension aims to:

- Display an AI icon when users focus on the LinkedIn message input.
- Open a modal for generating replies to LinkedIn messages using a static response.
- Demonstrate a functional and user-friendly interface that aligns closely with the provided Figma design.

## Tech Stack

- **Framework**: [WXT Framework](https://wxt.dev/) for Chrome extension development.
- **Languages**: React, TypeScript
- **Styling**: Tailwind CSS

## Features

The extension is designed to complete the following tasks:

1. **AI Icon Display**: The AI icon appears when the LinkedIn message input field is focused.
2. **Icon Disappearance**: The icon hides when the input field loses focus.
3. **Modal Opening**: When the AI icon is clicked, a modal opens at the center of the screen.
4. **Modal Dismissal**: Clicking outside the modal closes it.
5. **Input Command**: Users can enter a command in the modal’s input field.
6. **Static Response Generation**: Clicking "Generate" displays a static response:
   > Thank you for the opportunity! If you have any more questions or if there's anything else I can help you with, feel free to ask.
   - The **"Regenerate" button** is non-functional as specified.
7. **Insert Response**: Clicking the "Insert" button places the generated response into the LinkedIn message input field.

## Constraints

This project was built to align with the following constraints:

- **Framework**: Utilized **WXT Framework** as required.
- **Tech Stack**: Used only React, TypeScript, and Tailwind CSS.
- **Icons**: Exported SVG icons from Figma without any additional libraries.
- **Focus on Scope**: Only the specified functionality was implemented, with attention given to edge cases and code quality.

## Evaluation

The project fulfills all criteria specified in the assignment, including:

- **Problem-Solving Skills**: Implemented Chrome extension functionality with DOM manipulation using unfamiliar tools.
- **Adherence to Instructions**: Completed tasks (1 to 7) as instructed.
- **Attention to Detail**: UI elements match the Figma design closely.
- **Code Quality**:
  - **Readability**: The code is well-organized with descriptive variable and function names and necessary comments.
  - **Performance**: Optimized for efficient rendering and modularity.
  - **Reliability**: Edge cases were handled, with additional error handling added where necessary.
  - **Extensibility**: The code structure supports easy modifications and extensions.
- **Execution Speed**: Project completed within the given timeframe.

## Demo

Below is a video demo of the extension functionality:

<video controls src="https://youtu.be/UxAei1o5vrI" width="600" />

## Installation

To run the extension locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
