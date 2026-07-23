- Ollama
  ollama pull qwen2.5
  Emabedding:
  ollama pull mxbai-embed-large

# Listing the models

hp@hp-HP-Laptop:~/Documents/local-ai-agent$ ollama list
NAME ID SIZE MODIFIED  
mxbai-embed-large:latest 468836162de7 669 MB 3 minutes ago  
qwen2.5:latest 845dbda0ea48 4.7 GB 10 minutes ago  
qwen2.5:0.5b a8b0c5157701 397 MB 4 months ago  
qwen3:latest 500a1f067a9f 5.2 GB 4 months ago  
hp@hp-HP-Laptop-15:~/Documents/local-ai-agent$ ^C

# How to run

source venv/bin/activate
(venv) hp@hp-HP-Laptop-15:~/Documents/local-ai-agent$ python3 main.py

I'm sorry, but I can't provide an answer based on the information you've given. To determine the best pizza in town, I would need to see the relevant reviews that you mentioned. These reviews would ideally come from a variety of sources such as Yelp, Google Reviews, or other local review platforms. They should include feedback from customers who have visited the pizza restaurant and shared their opinions about the quality, taste, and overall experience of their pizza.

If you could provide me with some sample reviews or if you have a specific pizza restaurant in mind, I would be happy to help you analyze the data and determine which pizza might be considered the best in town.

## Final version with RAG

---

(venv) hp@hp-HP-Laptop-15:~/Documents/local-ai-agent$ python3 main.py

### output

hp@hp-HP-Laptop-15s~/Documents/local-ai-agent$ source venv/bin/activate
(venv) hp@hp-HP-Laptop-15:~/Documents/local-ai-agent$ python3 main.py

---

Ask your questionWhat are the vegan options?

Based on the reviews provided, the vegan options at this pizza restaurant seem to include:

1. **Vegan Cheese Option**: One review mentioned a vegan cheese substitute that was not well-received, describing it as tasteless and not properly balanced. However, another review highlighted a vegan pizza that uses cashew cheese made by the restaurant, which melts properly and is complimented for its fresh and seasonal vegetable toppings. This suggests that the restaurant offers a better quality vegan cheese option.

2. **Creative Specialties**: The restaurant's "Experimental" menu section is noted for its innovative and daring toppings, such as maple-glazed brussels sprouts, pancetta, and smoked gouda. While this particular review doesn't explicitly mention vegan options, it implies that the restaurant is open to experimenting with different and sometimes unconventional toppings, which could potentially include vegan-friendly alternatives.

In summary, for vegan diners, the restaurant offers a cashew cheese pizza with fresh toppings and is known for its willingness to experiment with new and innovative toppings that could be adapted to accommodate vegan preferences.
(venv) hp@hp-HP-Laptop-15:~/Documents/local-ai-agent$
