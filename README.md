# Python-CO--Aware-Energy-Scheduling-App
A Python/Gradio app where the user describes an appliance task in natural language. An LLM from Hugging Face extracts the appliance, duration and preferred time, then Python retrieves Energinet CO₂ data and finds the lowest-CO₂ period that fits. The Hugging Face LLM then turns the result into a simple recommendation for the user with relevant data.
