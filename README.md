# Lessons Card Deck Repository

This repository contains the data and images for a series of educational lessons, formatted as a card deck. Each lesson includes a set of assessment questions and exercises, along with a board brief image.

## Repository Structure

The repository is organized into several directories:

- `data/`: Contains the JSON files with the lessons data.
- `images/`: Stores the board brief images associated with each lesson.

### Data Format

Each JSON file in the `data/` directory has the following structure:

```json
[
  {
    "id": "1",
    "image": "../images/image1.jpg",
    "assessmentQuestions": [
      {
        "question": "What is Flexbox?",
        "answer": "Flexbox is a CSS layout model..."
      },
      // More questions
    ],
    "exercises": [
      // Exercise details
    ],
    "configuration": {
      // Configuration details
    }
  },
  // More lessons
]

## Images
Each lesson has an associated board brief image, stored in the images/ directory. The file names of the images are referenced in the corresponding lesson's JSON data.

## How to Use
To use this data:

- Clone the repository to your local machine.
- Access the JSON files for lesson data and images in your application.

## Contributing
Contributions to enhance the lessons or add new is done by VATSIM UK mentors involved in the creation, maintenance, and modification of the P rating syllabuses.

## License
This project is licensed under MIT, meaning you can use, modify, and distribute it as long as you follow the terms of the license.
