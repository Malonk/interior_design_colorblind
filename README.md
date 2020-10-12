# Interior design for color blind people

This is the final project of the 9 week Data Analytics bootcamp at Ironhack 2020. I'm happy to announce that this is the winning data project of the external Hackshow. 


### Problem statement

I'm color blind and one of my biggest hobbies is interior design. This isn't always easy, since sometimes I can't properly distinguish the colors. In order for me to understand what the colors are in my interior and what fits well together, I mainly ask friends for input. This isn't the most independent way of dealing with this issue. Therefore I've created a color checking tool to help me identify the colors in my interior and find other colors that match well with the main color scheme. 


### The tool

The tool I created will detect the 4 dominant colors of the interior and provide the color names. After, the tool will suggest complementary colors that could go well with these dominant colors to make the interior more vibrant. This works especially well when the interior is mainly having a monochromatic color scheme. 


### Methods

- Kmeans for clustering
- OpenCV for showing the images and clustering inside the image
- Webcolors to find color names and converting
- Colorharmonies library to find the complementary color


### Next steps

- For future development other color combinations can be explored, besides the complementary color scheme. 
- Explore the option of adding more color clusters or make the amount of clusters flexible, based on the interior. 
- Explore the tool for other creative fields, like fashion.
- Create an app for people to use
- Create a function where a personal photo can be uploaded


### Organization

Notebooks:
- exploration_phase_1.ipynb: Exploring how to work with images
- exploration_phase_2.ipynb: Further exploration of working with images, clustering and finding the color names
- final_demo.ipynb: The final tool 

Presentation:
- presentation_slides.pdf: The presentation I created and presented at the external Hackshow at Ironhack 

Data:
- wikipedia_color_names.csv: list of HEX codes, RGB values, color names

### Sources

Besides various python documentations:
- https://www.kdnuggets.com/2019/08/introduction-image-segmentation-k-means-clustering.html
- https://medium.com/analytics-vidhya/color-separation-in-an-image-using-kmeans-clustering-using-python-f994fa398454
- https://github.com/angristan/palette/blob/master/dataset/wikipedia_color_names.csv
- https://github.com/baptistemanteau/colorharmonies
