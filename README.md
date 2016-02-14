Fovea: Ansible Scripts
====================
These scripts are used to setup AWS/VPS instances with the following list of tasks and softwares:

* init
    - Create new ssh user 'deploy' with key-based authentication (disable password-based auth)
* deploy
    - Configure sendmail to use gmail
    - Setup Supervisor with process crash reporting
    - JDK 9
    - Scala environment, SBT
    - Node.js (nvm) w/ global modules (grunt, bower, etc.)
    - MongoDB
    - Python
    - OpenCV 2.4.10 (binary distribution)
    - Prediction.io
