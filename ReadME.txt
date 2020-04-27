# Distributed Machine Learning for Mobile Programmable Robots

Spring 2020 Final Design
## A Note On This Project

This is a robotics project, and as a result significant amount of time was spent on assembly, configuration, repair and maintenance of these robots. A SIGNIFICANT amount our time was devoted to research, learning how to build and implement mobility algorithms and work with the computer vision package.

As an example, Dr Amini requested that I spend time learning and explaining how object detection operates in detail, which is a research task rather than a programming task. I provided him with a detailed walkthrough of all the code, concepts, and implementations.

Having never worked with robotics OR computer vision, we had to learn.

## Installation

Unfortunately, there's no convenient way to install these files onto Zumi because there does not exist a way to install ANY files onto Zumi. It is functionality that was deliberately disabled by Zumi's manufacture.

* To get these files, go to your Zumi's dashboard > code
* Create a new module
* Copy the source code from the module you want
* Paste the source code into the new module you created

This is a problematic and error-prone process, but one that we had to cope with so long as we worked with a robot that is not intended for conducting research or doing extensive development. This is one of the key reasons we decided that each module needed to be self-contained; copy-pasting a complex system one file at a time would be extremely difficult.

It should not be necessary to modify any of these files as the project presumes you are running these modules from the Zumi environment. Naturally, they will not work without the robot.

## User Manual

These files can be executed like any other files in Jupyter Notebook: you simply click the play button adjacent to the code area to execute each module. (If you've worked with Jupyter Notebook and Zumi, this process will be extremely familiar).

In detail, this means:

1. Turn Zumi on
2. Find Zumi's signal in your wifi signals
3. Connect to Zumi using the signal name as the password
4. Find the file you wish to run and open it
5. Find the seciton of code you wish to run and click the run icon

## Directory Structure

Each file is self-conatined for the reasons previously outlined.

## License
[MIT](https://choosealicense.com/licenses/mit/)