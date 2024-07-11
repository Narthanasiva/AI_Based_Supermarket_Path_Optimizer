🚀 **Introducing My Latest Project: Quick-Supermarket Navigator** 🚀

I am thrilled to share my latest project, Quick-Supermarket Navigator, a cutting-edge application designed to optimize your shopping experience by providing the shortest path to find items in a supermarket. This project leverages advanced technologies in Natural Language Processing (NLP), Optical Character Recognition (OCR), and graph theory to create a seamless and efficient shopping journey.

🔍 **Project Overview:**
Quick-Supermarket Navigator is an AI-powered web application that helps users quickly locate items in a supermarket and provides the most efficient path to collect all items on their shopping list. Here’s a detailed breakdown of the project:

**Supermarket Layout Representation:**
I utilized NetworkX to create a graph representation of the supermarket layout, with nodes representing aisles and sections, and edges representing the paths between them. This allows for precise pathfinding and navigation.

**Natural Language Processing (NLP):**
Implemented KeyBERT for keyword extraction to understand the user's shopping list input.
Integrated SymSpell for spell correction and fuzzy matching to ensure accurate item recognition, even with minor spelling errors.

**Optical Character Recognition (OCR):**
Used PaddleOCR to extract text from images, allowing users to upload pictures of their shopping lists. This feature is especially useful for users who prefer handwritten lists or printed receipts.

**Pathfinding Algorithm:**
Leveraged Dijkstra's algorithm via NetworkX to find the shortest path between the entrance, each item on the list, and the checkout counter.
Created a visually appealing path visualization using Plotly, highlighting the route in different colors for each segment.

**User Interface:**
Designed a responsive and intuitive user interface with HTML, CSS, and JavaScript.
Included interactive features like voice commands and image uploads to enhance user experience.
The application dynamically shows the chat popup when the chat button is clicked, with the button animating to indicate activity.

**Enhanced User Experience:**
The voice command functionality uses webkitSpeechRecognition to convert speech to text, allowing users to verbally provide their shopping lists.
The chat feature provides a warm welcome message and asks users to input their shopping list.

**Detailed Path Explanation:**
Provided a natural language explanation of the path using NLP, making it easy for users to follow the directions step-by-step.

**💡Technical Skills Demonstrated:**
Python: Core language for backend development and algorithm implementation.
Flask: Used to build the web application and handle server-side operations.
NetworkX: Utilized for creating the graph and performing pathfinding algorithms.
KeyBERT & SymSpell: Implemented for NLP tasks to extract keywords and correct spelling errors.
PaddleOCR: Integrated for robust and accurate text extraction from images.
Plotly: Used for creating interactive and visually appealing path visualizations.
HTML, CSS, JavaScript: Designed a user-friendly and responsive interface, incorporating animations and interactive elements.

**🌟 Why This Project Stands Out:**
Innovative Integration: Combines advanced NLP, OCR, and graph theory to solve a real-world problem efficiently.
User-Centric Design: Focuses on enhancing the user experience with intuitive features and a seamless interface.
Versatile Application: The technologies and methodologies used can be adapted to various other industries and applications, such as warehouse management, indoor navigation, and more.
🔗 Explore More:
Interested in a demo or collaboration? Feel free to connect with me and let's discuss how we can work together to bring innovative solutions to life!



#AI #NLP #OCR #GraphTheory #Python #WebDevelopment #Innovation #ML #Flask
