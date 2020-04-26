Installation Instructions 
----------------------------------------------
- The game is Hosted and can be played here 
    -  https://littlebuddhaa.github.io/AGA-Project/   


- System Configurations

    For Effective Hosting 
                    Processor (CPU):	>Intel Core i5 (sixth generation or newer) or equivalent
                    Memory:	>4 GB RAM
                    Operating system — Windows , Mac, Ubuntu or equivalent



----------------------------------------------------------------------------------------------------------------------------------
- To view all the  dependencies open package.json
        dependencies 
                    node-sass: ^4.14.0,
                    react: ^16.10.1,
                    react-dom: ^16.10.1,
                    react-router-dom: ^5.1.2,
                    react-scripts: ^3.4.1

- But we donot need to install these packages one by one. Instead follow the below instructions [Works fine for all O.S]
   
                
                    [Make sure you have Node.js and NPM on your system - Instructions mentioned at the end of the file]

                    1. Download the folder MOODIGO into the desired location.

                    2. Open the terminal in the MOODIGO folder.

                    3. Install the dependencies using  'npm install' command [ To install all the dependencies]

                    3. Start local server using 'npm start'

                    4. Open  'localhost:3000'

----------------------------------------------------------------------------------------------------------------------------------

- Install Install Node.js and NPM - Ubuntu

Step 1 - Update your system
            sudo apt-get update
            sudo apt-get install git-core curl build-essential openssl libssl-dev python
Step 2 - Install Node.js
            1.First, clone the Node.js repository:

                    git clone https://github.com/nodejs/node.git
                    cd node

            2. Then compile and install Node like this (This might take a while, depending on your hardware.):

                    ./configure
                    make
                    sudo make install

            3. Then, check if node was installed correctly:

                    node -v
Step 3 - Install NPM
            Simply run the NPM install script:

                    curl -L https://npmjs.org/install.sh | sudo sh

            And then check it works:

                    npm -v
                    That’s all.

----------------------------------------------------------------------------------------------------------------------------------
- Install Install Node.js and NPM - Windows

Step 1: Download Node.js Installer
    In a web browser, navigate to https://nodejs.org/en/download/. 
    Click the Windows Installer button to download the latest default version.
    The Node.js installer includes the NPM package manager.

Step 2: Install Node.js and NPM from Browser

                1. Once the installer finishes downloading, launch it. Open the downloads link in your browser and click the file. Or, browse to the location where you have saved the file and double-click it to launch.

                2. The system will ask if you want to run the software – click Run.

                3. You will be welcomed to the Node.js Setup Wizard – click Next.

                4. On the next screen, review the license agreement. Click Next if you agree to the terms and install the software.

                5. The installer will prompt you for the installation location. Leave the default location, unless you have a specific need to install it somewhere else – then click Next.

                6. The wizard will let you select components to include or remove from the installation. Again, unless you have a specific need, accept the defaults by clicking Next.

                7. Finally, click the Install button to run the installer. When it finishes, click Finish.

Step 3: Verify Installation
                    1. Open a command prompt (or PowerShell), and enter the following:

                    node –v

                    2. The system should display the Node.js version installed on your system. You can do the same for NPM:

                    npm –v


----------------------------------------------------------------------------------------------------------------------------------
Layouts

        Cover Page 
        Moodigo land 
        Levels/Environment Pages
        Episode 
        Help Section 