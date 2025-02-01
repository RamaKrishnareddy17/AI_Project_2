Setup and Execution Steps
Download and Install CoppeliaSim Edu version.
Run the Simulator with the provided scene using the following command:

For macOS:
/Applications/coppeliaSim.app/Contents/MacOS/coppeliaSim -GzmqRemoteApi.rpcPort=23004 /users/Sadman/Downloads/drive/Intro_AI_Mix/mix_intro_AI.ttt

For Ubuntu:
./coppeliaSim.sh -GzmqRemoteApi.rpcPort=23004 /users/Sadman/Downloads/drive/Intro_AI_Mix/mix_intro_AI.ttt

Install required dependencies:
python3 -m pip install pyzmq  
python3 -m pip install cbor  
Copy the zmqRemoteApi folder to the project directory.

Run the Python script:
python3 exec_environment.py  
