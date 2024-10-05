# TerraAI: Enhancing Communities with AI-Driven Earthflow Preparedness
**Get access to your area's landslide proneness and geographical insights with just your location, powered by NVIDIA AI Workbench and CUDA!**

---

## 🌐 TerraAI Links
- **Blog Post:** [Read here](https://github.com/nikanair/TerraAI/blob/main/BLOGpost.md)
- **YouTube Video:** [Watch Here](https://www.youtube.com/watch?v=f0iQqKK1RZE)

---

## Introduction
In our rapidly changing world, climate change poses an increasing threat to global safety. According to research by NASA (National Aeronautics and Space Administration), climate change is driving more **volatile precipitation patterns** worldwide. This can lead to longer monsoon seasons and a heightened risk of landslides in affected areas. The recent [Wayanad tragedy](https://www.bbc.com/news/articles/cd108y8439po) in Kerala, India, underscores the urgent need for advanced technology that can monitor real-time landslide triggers globally.

![image](https://github.com/user-attachments/assets/80a9947d-12fa-44cc-8fb9-c70f97ac97e6)


Landslides become a critical hazard when:
1. Local communities lack access to reliable weather warnings.
2. Residents, particularly newcomers, are unfamiliar with the area's geographical risks.
3. There is limited awareness of the region’s history of landslide occurrences and trends.

---

## Current Solutions
1. **Landslide Early Warning Systems (LEWS):** These systems monitor rainfall, soil moisture, and ground movement to predict potential landslides but are often limited to specific geographical areas and can yield high false alarm rates.
2. **Satellite Remote Sensing:** Predicts landslides based on terrain changes and weather patterns. However, satellite data can be costly and may have time delays in availability.
3. **Drone-Based Monitoring:** Drones equipped with sensors collect high-resolution imagery and data to monitor slopes and terrain. Still, they require skilled operators for effective data collection and analysis.

---

## TerraAI
Introducing **TerraAI**, where safeguarding communities from landslide risks becomes a reality. Powered by **NVIDIA AI Workbench** and advanced geospatial analytics, TerraAI provides users with real-time insights and alerts, making safety accessible and fostering resilience in vulnerable areas.

![image](https://github.com/user-attachments/assets/0741a6d2-ef2a-4b00-9dfb-0c1d24793853)


**NVIDIA AI Workbench** accelerates TerraAI by speeding up AI model training, improving performance, and enabling scalable deployment for accurate disaster predictions in real-time. It enhances speed, scalability, and accuracy, helping the platform achieve its goal of empowering communities with reliable insights for better preparation and response to natural disasters.

TerraAI utilizes **Python 2.1** with **CUDA 12.2**, allowing AI models to run more efficiently by harnessing the parallel processing power of NVIDIA GPUs.

---

## Components
Built on **Microsoft Windows 11**, TerraAI is programmed in **Python** within **JupyterLab**, provided by NVIDIA AI Workbench. The platform also utilizes **transformers**, which offer tools for loading pre-trained models, fine-tuning them on custom datasets, and performing various **NLP** tasks like text generation and summarization—an indispensable component of our application. 

Additionally, TerraAI employs:
- **Geopy** for location identification
- **Seaborn** for statistical data plotting
- **Beautiful Soup** and **Requests** for web scraping tasks

For the user interface, we used **Gradio**, an open-source Python library for rapidly creating web applications to showcase machine learning models, along with **CSS** for styling.

---

## 🎬 TerraAI: How to See It in Action

### Installation
Ensure you have a GitHub account and NVIDIA AI Workbench installed on your device before following the steps below:

1. Fork the project to your GitHub namespace and copy the link.
2. Open AI Workbench and activate the context you want to clone into.
3. Clone the project onto your workbench by pasting the repo link.
4. Open the project and start JupyterLab to navigate to the code directory and open the file named **`terraAI_gradio.ipynb`**.

Be sure to install all the requirements from the **`requirements.txt`** file beforehand.

### Running
Navigate to the file **`terraAI_gradio.ipynb`** and run the code cell in JupyterLab. After a brief wait, you will see an output from Gradio displaying two links: a private link and a public link for running the model as a web app. Click on the public link to open a new browser tab.

![Screenshot 2024-10-05 121742](https://github.com/user-attachments/assets/12006122-4779-4727-98fe-267ec9ed85ab)

TerraAI will prompt you for your map location link, easily obtained from Google Maps. Simply open [Google Maps](https://maps.google.co.in), navigate to your desired location, click on the exact place you want to analyze, copy the link from the popup box, and paste it into the first input field. This step is illustrated in the [demo video](https://www.youtube.com/watch?v=f0iQqKK1RZE).

Answer a few basic questions about the current weather and enter your city name in the last input field. If you would like a detailed AI-generated report on past landslide events in your area, check the box and proceed to the **Submit** button.

Using AI technology and NVIDIA's GPU parallel processing, TerraAI will gather your location's coordinates, elevation details, and current weather conditions, including an overview of the current sky. Then, it will summarize past landslide events in your area and provide detailed reports on each event, including their locations and timings.

![Screenshot 2024-10-05 123606](https://github.com/user-attachments/assets/945bc879-005e-46c6-8292-d8972fc9b414)

Additionally, TerraAI offers visual data representations of the different trend patterns identified by AI in past landslides. For newcomers to the area, TerraAI provides emergency contact information, which can be invaluable during times of crisis.

We encourage you to use the app to uncover your region's geographical insights!

---

## ⭐ Review
TerraAI is an innovative solution poised to transform landslide detection and safety management. By utilizing advanced machine learning models and integrating cutting-edge tools like NVIDIA's AI Workbench, TerraAI empowers users to analyze geographical data and predict landslide risks effectively. This tool bridges the gap between technology and environmental safety, enabling communities, policymakers, and researchers to make informed decisions that can save lives and reduce property damage.

### **Empowering Communities with Intelligent Insights**
Through robust AI-driven algorithms, TerraAI offers real-time assessments of landslide risks based on historical data and environmental factors. Users can input geographic locations and receive comprehensive analyses, including the probability of landslides and safety recommendations. This user-friendly approach to data interpretation allows stakeholders—whether local governments, NGOs, or residents—to proactively address potential hazards and implement preventive measures.

### **A New Frontier in Disaster Management**
TerraAI signifies a pivotal advancement in disaster management by democratizing access to crucial information about landslide risks. It caters to both technical and non-technical users, ensuring that everyone can benefit from its insights without requiring specialized knowledge. As climate change continues to affect weather patterns and increase the frequency of natural disasters, TerraAI equips communities with the tools they need to adapt and respond, fostering resilience against environmental challenges.

---

## 🔗 References
- [NASA Study Finds Climate Extremes Affect Landslides in Surprising Ways](https://climate.nasa.gov/news/3218/nasa-study-finds-climate-extremes-affect-landslides-in-surprising-ways/#:~:text=Water%20triggers%20landslides,%20and%20knowing%20how%20landslides%20react%20to%20record)  
- [NVIDIA AI Workbench](https://www.nvidia.com/en-us/deep-learning-ai/solutions/data-science/workbench/)
