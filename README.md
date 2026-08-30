# n8n AI Food Scene Generator

I built this project to transform a simple food image into a more realistic lifestyle or restaurant-style image.

The workflow takes a food image as input, analyzes the dish, creates an AI prompt, and sends the prompt to an image-generation model. The final result places the food into a realistic scene with a person and restaurant environment.

## Workflow

The automation follows these main steps:

1. Receive the food image
2. Upload the image for processing
3. Analyze the food image using AI
4. Generate a detailed image-generation prompt
5. Send the prompt to the image-generation API
6. Wait for the image to finish generating
7. Retrieve the generated image
8. Return the final output

## How It Works

```text
Food Image
    |
    v
Upload Image
    |
    v
Analyze Image
    |
    v
Prompt Generator
    |
    +---- OpenAI Chat Model
    |
    +---- Think Tool
    |
    v
Image Generation API
    |
    v
Wait
    |
    v
Get Image
    |
    v
Final Generated Scene

## Example
### Input

A standalone food image is provided to the workflow.

### Output

The workflow generates a new lifestyle image where the same type of food is shown in a realistic restaurant environment with a person.

## Technologies Used

n8n
OpenAI
AI image analysis
AI prompt generation
Fal AI API
HTTP Request
Image-generation APIs
Workflow automation

## What I Learned

While building this project, I gained hands-on experience with:

AI image analysis
Prompt engineering
Image-generation workflows
Connecting AI models with n8n
Working with external APIs
Handling asynchronous image-generation jobs
Using wait and polling logic
Retrieving generated images automatically
Building an end-to-end AI automation workflow

## Security

API keys, passwords, access tokens, and private credentials are not included in this public repository.

Anyone importing the workflow will need to configure their own API credentials before running it.

## Project Goal

The goal of this project is to demonstrate how generative AI and workflow automation can turn a basic product or food image into more engaging lifestyle content for use in restaurants, cafés, food marketing, and social media.

## Author

Kartik Patel

