[FastAPI : This Project Created By Kollathee Wis.]

[Tech Stack]

    Programing Language : Python 3.12

    Environment : Anaconda

    API Framework : FastAPI 

    Deployment Server : Ubuntu 22.04.2 LTS

    Deployment Tool : Docker 22.0.7 , Docker Compose v2.21.0

[Step Set Up]

[1. Create Python Environment Using Anaconda]

    1.1 Download and Install Anaconda

    1.2 Open Anaconda Prompt And Use This Command

        conda create -n FastAPI_01 python=3.12

        conda activate FastAPI_01

        conda install -c anaconda ipykernel

        python -m ipykernel install --user --name=FastAPI_01

[2. Install Oracle Client]

    On Windows

    1. Open visual studio installer

    2. Install : Desktop development with C++ , Data storage and processing build tools , .Net desktop build tools


[3. Start Project]

    3.1 Open Visual Studio Code

    3.2 Python: Select Interpreter => FastAPI_01

    3.3 Open CMD (Activate Conda)

        3.3.1 pip install -r requirements.txt

        3.3.2 uvicorn main:app --reload

[4. Deploy]

    4.1 Create Dockerfile , docker-compose.yaml

    4.2 Import project to Ubuntu Server

    4.3 Open Ubuntu and cd Project

    4.4 Run This Command 

        sudo docker compose build

        sudo docker compose up -d

        sudo docker compose up

        sudo docker compose down