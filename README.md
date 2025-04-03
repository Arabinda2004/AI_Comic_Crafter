# AI_Comic_Crafter
ComicCrafter AI is a locally running generative AI-powered comic creator that transforms user-provided prompts into engaging comic-style stories, all on edge devices—ensuring fast, efficient, and creative storytelling.

📖 AI Comic Crafter
AI Comic Crafter is a web-based application that transforms user-provided textual narratives into visually appealing comic strips using advanced AI models. It allows users to generate short stories and convert them into comic panels, making the comic creation process fast, accessible, and engaging.

🚀 Features
AI-Powered Story Generation – Uses LLaMA for generating engaging stories based on user input.

AI-Powered Image Generation – Uses Stable Diffusion to create high-quality comic-style visuals.

User-Friendly Interface – Built with Streamlit for seamless user interaction.

Customizable Genres & Styles – Supports multiple genres and comic styles.

One-Click Download – Generates a ZIP file containing all comic panels for easy sharing.

📌 How It Works
User Inputs Story Elements – Enter four key story components:

Introduction: Setting and character introduction.

Storyline: Main events of the story.

Climax: Turning point or major event.

Moral: Key takeaway or lesson.

AI Generates the Story – The LLaMA model processes the input and generates a well-structured story.

AI Creates Comic Panels – The Stable Diffusion model converts each part of the story into a comic-style image.

Download & Share – Users can download the comic panels as a ZIP file.

🛠️ Technologies Used
Streamlit (1.44.1)

LLaMA (llama-cpp-python 0.3.8)

Stable Diffusion XL (2.1)

Python (3.11)

Pyngrok (7.2.3)

Torch (2.6.0+cu124)

Transformers (4.50.2)

Diffusers (0.32.2)

OpenCV (4.11.0.86)

NumPy (2.0.2)

Pandas (2.2.2)

🏗️ Installation & Setup
🔹 Prerequisites

Ensure you have Python 3.11 installed on your system.


🔹 Install Dependencies

pip install streamlit torch transformers diffusers opencv-python numpy pandas pyngrok llama-cpp-python

🔹 Run the Application

streamlit run AI_Comic_Crafter.ipynb



💡 Future Enhancements
Support for animated comic panels

Multi-page comic strip generation

Advanced customization options for comic styles and themes
