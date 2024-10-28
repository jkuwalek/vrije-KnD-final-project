# How to run

This project uses [pixi](https://pixi.sh/) to manage decencies.

1. Install [pixi](https://pixi.sh/)
2. Open the src/final_result/final pipeline.ipynb
3. Select the pixi environment as the kernel
4. Run the notebook

# Structure

### src/steps

This folder contains some draft notebook that we used while prototyping the final one. The notebooks in that directory are not expected to work.

### src/final_result

This folder contains our final project. The final pipeline is our main and only data processing pipeline. This file loads the csv data, queries the sparql endpoint, runs the reasoner, and visualizes and analyzes the covid19 spread data.

In order to run the pellet reasoner

1. Download Java Development Kit (JDK):
    Go to Oracle's JDK download page or OpenJDK for an open-source version.
    Download the latest version for your operating system.

2. Install JDK:
    Run the installer you downloaded and follow the instructions.
    During installation, note the installation path (e.g., C:\Program Files\Java\jdk-<version> on Windows).

3. Set up the Java Environment Variable (if needed):
    On Windows:
        Go to Control Panel > System > Advanced System Settings > Environment Variables.
        Under "System variables," click New and set the variable name as JAVA_HOME and the variable value as the path to your JDK (e.g., C:\Program Files\Java\jdk-<version>).
        Find the "Path" variable, click Edit, and add %JAVA_HOME%\bin to the list.
    On macOS/Linux:
        Open a terminal and edit the .bashrc or .zshrc file.
        Add the line export JAVA_HOME=/path/to/jdk (replace with your JDK path).
        Add export PATH=$JAVA_HOME/bin:$PATH to add Java to your PATH.

4. Verify the Java Installation:
    Open a terminal or command prompt and type: bash java -version
    You should see the Java version if the installation was successful.
    If not, restarting the computer might fix it.