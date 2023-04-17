# plan
[x] explore and understand the CLIP interaction notebook. 
- Know how to take an image and encode then compare it to text
[x] load images into vector db
[x] explore the space of duplicate image search
[x] explore similar image search
[x] explore search of images based on text
[x] negative prompt 
[x] reverse caption
[ ] portfolio search (multiple images at the same time)


# Scenarios we need to test
- I like this image, find me others like it
- recommender engine for similar items that I've looked at recently
- semantic search instead of keyword search based on predefined tags
- semantic search of images
- reverse image search
- define likes and we recommend similar items for you



# Analysis
- It seems using OpenAI clip on MNIST is shit. This was noted in their paper. 
- However it looks really interesting on a dataset such as Modern Architecture. See [Modern Architecture](/workspaces/fast.ai/vectordb/modern-architectures.ipynb)



# Interesting Links

https://colab.research.google.com/github/robgon-art/open-clip/blob/main/Create_Captions_with_OpenCLIP.ipynb
