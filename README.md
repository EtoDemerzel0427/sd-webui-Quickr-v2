# Quickr-V2

In this version, we have developed our workflow by building upon the existing codebase from Deforum-art. 
They offer a powerful interface and a wide range of robust utilities for us to leverage. We reused some of their
video processing code and added our own algorithms to the workflow.
This workflow serves as an extension of the AUTOMATIC1111/Stable-Diffusion-WebUI.

## How to use
To utilize the entire workflow, you need to set up a complete pipeline for Stable Diffusion and its WebUI (will introduce in the next section). 
This process involves numerous options and buttons to choose from, making deployment and usage more complex. 
Additionally, to run the entire pipeline, you must have a GPU with at least 8GB of memory. 
For video processing with controlNet, a minimum of 24GB of CPU memory is also required (based on my own experience, 
I initially used a 16GB CPU memory, and it failed to load the controlNet model).

**To facilitate easier testing of our code by the Professor/TA**, we have created an example folder 
containing some scripts. These python scripts demonstrate our key algorithms and illustrate 
how we rapidly prototype our ideas. The extension is built to provide the internal algorithms with a graphical
user interface and an integration with Stable Diffusion configurations.

### Example

The `fspbt` folder consists of the code and the data needed for a simple run of the Few-Shot Patch-Based Training algorithm.
There is another README.md file in the folder that explains how to run the code.




