# Generative Art - Personal Experiment
## Animated Random Fractal Trees

I was playing around with the p5.js library to help my sister with her generative art coding assignment, and exploring the simple method of developing recursive fractal trees. I was intrigued by how similar yet uncanny fractal trees looked to trees you would find naturally.

I spend some time editing and playing with the fractal tree code I generated in an attempt to make them appear more natural, while adding features such as leaves, blossoms, colour, midpoint branching, and variable branch width. By introducing random branch generation, and fine-tuning the parameters of the system, I was able to get very interesting and more "natural" looking trees while still retaining a clean and flat stylization (See image below).

![Generated image of stylized random fractal trees](treespng.png)

Following creating a stylized fractal tree, I wanted to animate them as they ran so it appeared as if they were "swaying" in the wind. Through some clever use of sinusoidal functions and jerry-rigging a periodic variable, I was able to get dynamic and satisfying swaying motion that looks somewhat like wind. 

## Notes:
- The generated trees are random. As such, you may have really nice looking trees, or very unique looking trees. If you want to get a new set of trees, refresh the browser page.
- If you modify the code, you can change the tree generation parameters, the wind, the background, and where the trees are. 

## Extensions
- Adding sliders and controllers for changing parameters
- Add a refresh button as opposed to forcing user to refresh the page
- Include an optional starting seed parameter, and show the random seed used for the current generation.

## Try it out:
- You can view it and play with the code [directly from p5js.org](https://editor.p5js.org/NathanBHart/full/8I1QjYVTm6) (no download required)
- You can download the repository, and open the index.html file in your browser. It will load the p5.js library via an external CDN, so you will not have to run a local server.

### **Enjoy!**

