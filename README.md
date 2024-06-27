AI_Hybrids - First Iteration
This project is the first iteration of a Python codebase that leverages OpenAI's API to generate prompts and images of randomly selected hybrid animals. It showcases the foundational work done in developing a basic model to create unique and imaginative animal hybrids.

Project Description
The initial version of this project aimed to:

Utilize OpenAI's API to generate creative prompts for hybrid animals.
Use these prompts to generate images of the described hybrid animals.
Provide an easy-to-understand interface for displaying generated prompts and images.
Current Status
This basic version of the hybrid animal generator is currently a portfolio project demonstrating the initial efforts and methodology. While it provides a glimpse into the foundational work, it lacks the advanced features and refinements planned for future iterations.

Future Development
A more advanced version of this project is under development and will include:

Categories of biome for each animal, allowing users to select specific biomes for the hybrid animals.
Code checks to ensure that two animals of the same genus or biome are not combined, guaranteeing unique and imaginative hybrid animals that do not closely resemble real-life animals.
Stay tuned for updates and the official release of the advanced version!

Feel free to reach out if you have any questions or need assistance with running the code.

Installation
To explore the initial version locally, follow these steps:

sh
Copy code
git clone git@github.com:yourusername/hybrid-animal-generator.git
cd hybrid-animal-generator
Usage
Set up your OpenAI API key as an environment variable:
sh
Copy code
export OPENAI_API_KEY='your-openai-api-key'
Run the script:
sh
Copy code
python generate_hybrid_animals.py
Dependencies
Ensure you have the following dependencies installed:

Python 3.7+
OpenAI API client (openai)
Install dependencies using pip:

sh
Copy code
pip install openai
Example Output
Here's an example of what the generated prompts and images might look like:

Prompt: "Create an image of a hybrid animal that is part lion, part eagle."
Image: 
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

