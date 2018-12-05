# MachineLearning

## Installing environment

1. Download latest version of Anaconda.

2. Proceed with the installation but skip the step where you need to download VS.

3. Open Anaconda Navigator and install VS from GUI.

4. Close Anaconda Navigator and open Anaconda Prompt

5. Downgrade python to a Keras & Tensorflow compatible version. For example, to downgrade to python 3.6 use the following command:

      conda install python=3.6

6. Create a new  anaconda environment with the following command:

      conda create --name PythonGPU

      This will create a virtual anaconda environment that you can break without breaking anaconda.  I named my environment PythonGPU.

7. Activate environment with:

      activate PythonGPU

8. To deactivate the Python GPU environment simply use the following command. Do not deactivate your environment yet. We are about to install all the good stuff;)

     deactivate PythonGPU

9. Install the Keras & Tensorflow GPU versions with:

      conda install -c anaconda keras-gpu

10. Install Spyder in this new environment with:

      conda install spyder

11.  Install the Pillow library needed for CNNs:

      conda install Pillow

12. Install Pandas that are used with the ANN section of this course:

      conda install -c anaconda pandas 

13. Install matplotlib:

      conda install -c anaconda matplotlib
      
14. Install sklearn:

      conda install -c anaconda scikit-learn

