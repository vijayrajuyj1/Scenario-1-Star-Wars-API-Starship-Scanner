# Scenario-1-Star-Wars-API-Starship-Scanner.

Task: 
Develop a Python or Bash tool that retrieves all starships and their pilots from a given Star Wars film using the Star Wars API (SWAPI).

In this task, we are using Python 3 to retrieve all starships and their pilots from a given Star Wars film.

Steps to Run the Project:

1️⃣ Install Python 3

If Python 3 is not installed, install it using:
$ sudo apt install python3 -y

To check the version:
$ python3 --version

2️⃣ Install Required Dependencies

Install the requests library for handling API requests:
$ pip install requests

For Python 3, use:
$ pip3 install requests

3️⃣ Clone This Repository

git clone <repository-url>
cd <repository-name>

4️⃣ Python Script for Retrieving Starships and Pilots

The script starships_pilots.py is available in this repository.

5️⃣ Execute the Script with a Film Name

Run the script using the following command:
$ python3 starships_pilots.py "A New Hope"


6️⃣ Expected Output (JSON Format)

The output will be in JSON format, showing the film name, starships, and their pilots:

{
    "film": "A New Hope",
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






