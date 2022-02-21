# Genetic-Algorithm

Genetic Algorithm simulator made using MATLAB 

Genetic Algorithm is a random-based classical algorithm inspired by Charles Darwin's theory of natural evolution. This algorithm reflects the process of natural selection where the fittest individuals are selected for reproduction in order to produce offspring of the next generation. In this example, each square represents an 'insect', there are 64 insects in total laid out by an 8x8 grid. The colour of each insect is randomly initalized, as well as the background colour. It is seen that as each generation (cycle) passes, the insects that are most alike to the background colour survive, and thus reproduce amongst themselves to have offspring that share similar qualities. While insects whose colours are most unlike the background colour essentially die away.


<img width="553" alt="Screenshot 2022-02-21 at 2 45 19 PM" src="https://user-images.githubusercontent.com/71420919/154977432-1f8c1697-d1bc-46cf-bba9-396a8014063e.png">


## White environment
![White Genetic Algo](https://user-images.githubusercontent.com/71420919/154976657-88fad420-fcdc-481c-8192-a3f602aed81e.gif)

## Black environment
![Black Genetic Algo](https://user-images.githubusercontent.com/71420919/154976672-f86eaaa1-7874-4a8d-95e7-379b98805723.gif)

## Methodology of how it works
<img width="181" alt="Screenshot 2022-02-21 at 2 46 03 PM" src="https://user-images.githubusercontent.com/71420919/154977555-9cd35a82-b9ab-43b1-ab9d-faffb362120e.png">

## Crossover of genes and chromosones
<img width="553" alt="Screenshot 2022-02-21 at 2 45 19 PM" src="https://user-images.githubusercontent.com/71420919/154977432-1f8c1697-d1bc-46cf-bba9-396a8014063e.png">

This is where some high school biology becomes useful, for example if you have two parents:
-parent 1 = 000000
-parent 2 = 111111
a crossover of genes between parent 1 and parent 2 can result in offspring having:
-offspring 1 = 111000
-offspring 2 = 000111
this is because half of the genes in an offspring come from parent 1 and the other half from parent 2.
