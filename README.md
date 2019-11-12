# Quantum Zentanglement

## How to make a Zentangle:
### Batch Files: 
* Launch-Zentangle-HB.bat : Automatically generate using the half-black fitness scheme
* Launch-Zentangle-HB3Color.bat : Automatically generate using the half-black-3-color fitness scheme
* Launch-Zentangle-Interactive.bat : Evolve interactively using Picbreeder
* Launch-Zentangle-RandomBW.bat : Automatically generate using the random fitness scheme in black-white only
* Launch-Zentangle-RandomColor.bat : Automatically generate using the random fitness scheme in color

### Windows 
* Double click on the Launch-Zentangle-Interactive.bat to create Zentangles interactively or choose any of the other 4 batch 		   files with the Launch prefix to automatically generate Zentangles using the fitness schemes random, half-black, half-black-3-color

### Mac/Linux/Unix 
* Run bash Launch-Zentangle-Interactive.bat from the terminal to create Zentangles interactively or choose any of the
  other 4 batch files with the Launch prefix to automatically generate Zentangles using the fitness schemes random, half-black,
  half-black-3-color

### Other
* Run PicbreederTask.java from the terminal or an IDE

### Interactive Evolution
* Evolve images until you find some that you think would make interesting patterns
* Toggle between mathematical functions and color settings such as stark and black-white
* Increase or decrease the mutation rate for more change between generations
* Select any number of images and press the Z (Zentangle) button! It may take take a few moments.
* Some of the images will be patterned using WFC and up to 2 will be used as template images
* The details of how a Zentangle is formed depend on how many images contribute to the Zentangle
	* 2 - 1 image used for template and pattern, 1 image used for distinct pattern
	* 3 - 1 image used for template, 2 images used for distinct pattern
	* 4 - 1 image used for template and pattern, 1 image used for template, 2 images used for distinct patterns
	* 5 - 2 images used for templates, 3 images used for distinct patterns
	* 6 and greater - 1 image used for template, remaining images used for combined patterns
* Your image will appear in a new window 


For this project, we have edited InteractiveEvolutionTask, which is implemented by a few other "tasks", such as breedesizer and animationbreeder. As a result, these tasks will also have a Zentangle button, but it will not function in those tasks.

- Sarah Friday, Anna Krolikowski, Dr. Schrum, and Alice Quintanilla

# Below is the readme file that originally was included in CPPNArtEvolution  

This project contains several forms of interactive art evolution, all based on CPPNs. All code in this project is part of the main [MM-NEAT project](https://github.com/schrum2/MM-NEAT), but this project is simplified to remove much extraneous code not required for interactive evolution. This project is also much easier to use and launch. Just follow the instructions below:

## Windows

Just double-click any of the batch files with the Launch prefix:

* Launch-Picbreeder.bat: Evolve 2D pictures, just like the original [Picbreeder](http://picbreeder.org/)
* Launch-AnimationBreeder.bat: Evolve 2D animations!
* Launch-3DObjectBreeder.bat: Evolve 3D shapes, in a manner similar to [Endless Forms](http://endlessforms.com/)
* Launch-3DAnimationBreeder.bat: Evolve 3D animations!
* Launch-Breedesizer.bat: Evolve tones that can be used to play MIDI files, similar to the original [Breedesizer](http://bthj.is/breedesizer/)

These batch files all use the CPPNArtEvolution.jar file that is already in the repository. However, if you want to recompile this jar file, you can use the build.xml ANT build script, or create an executable jar file with the class edu.southwestern.MMNEAT.MMNEAT as the main class.

## Mac/Linux/Unix

The batch files listed above do not use any Windows-specific commands, so they can easily be executed as bash scripts as well. Alternately, you can just copy-paste the command inside of any of these files to your terminal.

## Help

If you need any help, then please contact me at schrum2@southwestern.edu!

Also, you can evolve neural networks for lots of other interesting applications by using the original [MM-NEAT project](https://github.com/schrum2/MM-NEAT), which contains the interactive evolution code from this project, along with code to evolve agent behavior for various tasks (Ms. Pac-Man, Tetris, and Mario to name a few)

## Citing

If you use any of this code for any project or publication, please cite the following paper:

```
@inproceedings{tweraser:gecco2018,
	title={Querying Across Time to Interactively Evolve Animations},
	author={Tweraser, Isabel and Gillespie, Lauren E and Schrum, Jacob},
	year={2018},
	booktitle={Proceedings of the Genetic and Evolutionary Computation Conference (GECCO 2018)},
	month={July},
	numpages = {8},
	url = {https://people.southwestern.edu/~schrum2/SCOPE/tweraser.gecco18.pdf},
	doi = {10.1145/3205455.3205460},
	publisher = {ACM},
	address = {New York, NY, USA},
	location={Kyoto, Japan}
}

```
