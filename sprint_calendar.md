# Computer Vision Project <!-- omit in toc -->

**[Github Repository](https://github.com/YamanduGermano/computer-vision-project/tree/main)**

## Summary <!-- omit in toc -->

- [Project objective:](#project-objective)
- [Calendar](#calendar)
- [Sprints](#sprints)
  - [Sprint #1](#sprint-1)
  - [Sprint #2](#sprint-2)


## Project objective:

```
How to improve skin-disease detection in dark skin-tones using CNNs.
```

## Calendar

| Date  | Name      | Objective                                                                                  |
| ----- | --------- | ------------------------------------------------------------------------------------------ |
| 07/04 | Sprint #1 | Basic project structure and setting up the database. First tests with simple detection CNN |
| 14/04 | Sprint #2 | Implementing segmentation to improve classification performance                            |
| 28/04 | Sprint #3 | Creating web interface to use with the model                                               |
| 05/05 | Sprint #4 | Connecting web interface with the model and polishing last details                         |
|       |           |                                                                                            |
| 12/05 | Sprint #5 | Polishing phase                                                                            |


## Sprints

### Sprint #1

**Resources needed:** AWS resources to host the model backend.

### Sprint #2

The model couldn't be trained on a personal notebook with 16 GB of ram. The estimated size required to train the entire database of images is around 40 GB.
A smaller version was tested with a total of 500 input images and it required 8 GB to be loaded.

More work will be necessary in the following week in order to get the model working.

**Loading the database:**
!["Loading the database"](images/1_17-04.png)

**Building the model**
!["Building the model"](images/2_17-04.png)