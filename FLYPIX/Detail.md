<h1>AI POWERED ASSISTANT </h1>
# FLYPIX – AI-Powered Travel & Destination Assistant

FLYPIX is an AI-driven chatbot that helps users explore flight ticket prices and visualize their travel destinations.  
It combines **Anthropic’s LLM**, the **Amadeus Airline API**, **custom tools**, and **Gradio UI** to create a smooth and engaging conversational travel experience.  

---

## Features

- Conversational AI powered by **Anthropic Claude** for natural dialogue.  
- Real-time flight offers using the **Amadeus API** (one-way & return).  
- Custom tools that enable the LLM to fetch structured airline results.  
- AI-generated images of the destination city via a **Hugging Face model**.  
- Interactive **Gradio-based user interface** for an intuitive chat experience.  

---

## Workflow

1. User interacts with FLYPIX through a **Gradio chat interface**.  
2. The LLM processes the query and decides whether to call a **custom tool**.  
3. The tool queries the **Amadeus API** to fetch flight offers.  
4. FLYPIX formats the results into a conversational response.  
5. Optionally, FLYPIX generates an **AI image of the travel destination**.  

---

## Tech Stack

- **LLM**: Anthropic Claude  
- **Airline API**: Amadeus  
- **Image Generation**: Hugging Face Diffusion Model  
- **Frontend**: Gradio  
- **Backend**: Python  

---

## Purpose

The goal of FLYPIX is to demonstrate how **Large Language Models** can be extended with:  
- Custom tools for external API integration  
- Real-world airline ticketing and travel use cases  
- Image generation for enhanced user engagement  

---

## Example Usage

**User:**  
"Find me the cheapest round-trip flight from Lahore to Dubai on 2025-10-25."  

**FLYPIX Response:**  
Returns flight prices from the Amadeus API, along with an AI-generated image of Dubai.  

---

## Future Improvements

- Support for multi-city flight searches  
- Hotel and travel package integration  
- Personalized travel itineraries and recommendations

## API Information
- The API I used doesn't support real time as it requires production with payment
- so I used sandbox 
