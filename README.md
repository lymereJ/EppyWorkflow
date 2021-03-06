# EppyWorkflow

## Description
This repository contains a set of Python functions and a master CSV file that can be used as a workflow using [Eppy](https://github.com/santoshphilip/eppy) to create and modify [EnergyPlus](https://github.com/NREL/EnergyPlus) models.

## Why?
I like to use [Eppy](https://github.com/santoshphilip/eppy) to modify [EnergyPlus](https://github.com/NREL/EnergyPlus) models in order to run parametric simulations. However, I've always been missing a central repository containing all the functions that I have created in the past. With this workflow I can reuse any of the functions that I have previously created for any projects. Only a few examples of functions are present on the repository, all the others are hosted locally.

## How does it work?
+ Write Python functions using [Eppy](https://github.com/santoshphilip/eppy) 
+ Add these functions to the master CSV file or the BatchProcessingCreator excel workbook
+ Add parametric runs to the master CSV file or the BatchProcessingCreator excel workbook
+ For each run provide the corresponding argument for each function (if the function does not apply just input "-")
+ Run the `Main.py` script

Hop'la, you've got yourself your modified EnergyPlus model(s) ready for simulation:exclamation:

## Example
To get a better idea of the workflow, there is a small example in the example folder of this repo.

## Structure

* Root
  * :memo: Main.py
  * :memo: importdir.py
  * :memo: BatchProcessing.csv
  * :file_folder: Functions
    * :memo: Function1.py
    * :memo: Function2.py
    * etc...