# Scenario-1-Star-Wars-API-Starship-Scanner.

Task : 
Develop a Python or Bash tool that retrieves all starships and their pilots from a given
Star Wars film using the Star Wars API.

In this task i am using python3 for retrieves all starships and their pilots from a given
Star Wars film using the Star Wars API.

STEPS:

 1. Download Python3 from the official website 

$ sudo apt install python3 -y

2. Check the version 

$ python3 --version

3. Write the python script to  retrieves all starships and their pilots from a given
Star Wars film using the Star Wars API.

Note: The python script was there in this repo (starships_pilots.py)

4. Excute that file with command-line arguments

   -> python3 starships_pilots.py "A new Hope"

5. The Expected output: 

   {
    "film": "A new hope",
    "starships": [
        {
            "starship": "CR90 corvette",
            "pilots": []
        },
        {
            "starship": "Star Destroyer",
            "pilots": []
        },
        {
            "starship": "Sentinel-class landing craft",
            "pilots": []
        },
        {
            "starship": "Death Star",
            "pilots": []
        },
        {
            "starship": "Millennium Falcon",
            "pilots": [
                "Chewbacca",
                "Han Solo",
                "Lando Calrissian",
                "Nien Nunb"
            ]
        },
        {
            "starship": "Y-wing",
            "pilots": []
        },
        {
            "starship": "X-wing",
            "pilots": [
                "Luke Skywalker",
                "Biggs Darklighter",
                "Wedge Antilles",
                "Jek Tono Porkins"
            ]
        },
        {
            "starship": "TIE Advanced x1",
            "pilots": [
                "Darth Vader"
            ]
        }
    ]
}


   
