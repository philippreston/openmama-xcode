openmama-xcode
==============

Xcode Project for building OpenMAMA

Usage
=====
Simply drop the project in the top level folder of your Open MAMA Checout to start.

Then you will need to set the following User Variables in the OpenMama Project:

| Variable       | Description                                                                              |
|:---------------|:-----------------------------------------------------------------------------------------|
| AVIS_HOME      | Folder for the Avis client installation - required for Avis bridge                       |
| AVIS_VERSION   | Version of the Avis client installation for version information in build for Avis bridge |
| GTEST_HOME     | Home folder for Google Test framework for use in Unit Test builds                        |
| JAVA_HOME      | Java Installation director for JNI builds                                                |
| OPEN_MAMAHOME  | Automatically set to $(PROJECT_DIR)                                                      |
| QPID_HOME      | Folder for the QPID Proton client installation - required for Qpid bridge                |
| QPID_VERSION   | Version of th QPID Proton client installtion for version information in builds for Qpid  |


Version
=======

Built on Xcode v5.0.2
