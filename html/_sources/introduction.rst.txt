Introduction
############

The eIQ Toolkit is a machine-learning software development environment that enables the use of ML algorithms on NXP microcontrollers, microprocessors, and SoCs.

The eIQ Toolkit is for those interested in building machine learning solutions on embedded devices. A background in machine learning, especially in supervised classification, is helpful to understand the entire pipeline. However, if the user does not have any background in the areas mentioned above, the eIQ Toolkit is designed to assist the user.

The eIQ Toolkit consists of the following three key components:

* eIQ Portal
* eIQ Model Tool
* eIQ Command-line Tools

The eIQ Portal is designed to help you with image classification and object detection tasks without deep machine-learning knowledge. Using the eIQ Portal easy-to-use Graphical User Interface (GUI), you can create a project and import a custom dataset into it to solve a specific real-life problem. Then you select the model that fits your problem the best and train and evaluate it over the dataset you imported. The evaluation process gives you information about how accurate the model that you trained is and how fast it runs on the target architecture. In addition to this, the eIQ Portal provides very efficient techniques to improve your model performance, customized for each target type.

The eIQ Model Tool is used for the subsequent analysis of your models, including model and per-layer time profiling.

For users who prefer it, NXP offers a set of command-line tools (the eIQ Command-line Tools), which also include a self-contained Python environment.

.. note::
    To use the eIQ Command-line Tools, it is important either to launch them using the COMMAND LINE button from the home screen or run the <eIQ_Toolkit_install_dir>/bin/eiqenv.bat script, which sets up the command- line environment.