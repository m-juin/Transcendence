# ft_transcendence

Final Project of the 42 School main cursus.

Ft_transcendende is a Single Page Application website where you can play 3D Pong and Battleship with other players, including live chat, tournaments, games historic and statistics and other features

**Warning**
This is a student project and was not intended to be put on line. This is the reason why we let a .env file if you want to test it.

## Stack

### Frontend
* HTML
* CSS
* JS

### Backend
* Django
* PostgreSQL

### Blockchain
* Solidity

## Usage
The site can be launched either with ```make``` or ```docker-compose up --build```
You can the connect on https://localhost or https://<host ip>

## Content
The subject requested to follow a mandatory and let the choice between a list modules for the rest of the proejct.  

### Mandatory
* Technical requirement
    * Single Page Application
    * Frontend develop in pure vanilla Javascript
    * Compatibility with latest stable Google Chrome version
    * User shouldn't encounter unhandled error
    * Project must be launched with one command : `docker-compose up --build`
* Game:
    * Propose a Pong game with Player vs Player and tournament. The site must have matchmaking system.
* Security:
    * Passwords in the database must be hashed
    * Protection agains SQL injection/XSS
    * HTPPS connexion
    * Form validation for user input

### Modules
#### Django as backend
#### PostgreSQL database
#### Tournament score stored in the Blockchain
Store the tournaments securely on a blockchain using a testing blockchain environment. 
Using Ethereum as blockhain and Solidity as programming language.
#### Standard user management, authentitacation, users across tournaments
* Subscription and log on the website in a secure way
* Possibility to update user informations
* Friends list features
* Match and stat history
#### Remote players
Play against player on other computer
#### Other game
Add another game with the same requirements
#### Live Chat
Create a chat that allow users to:
* send direct messages
* block users
* invite user to game
* access other user profile
* send notification for next tournament game
#### IA Opponent
Introduce an AI opponent that provides an engaging and challenging gameplay for the users
#### User and Game Stats Dashboard
Create a user friendly dashboards that provides users insight on their own statistics
#### Two-Factor Authentication and JWT
Enhance security and user authentication by introducing Two-Factor Authentication and utilizing JSON Web Tokens 
#### 3D graphics
Use advanced 3D techniques to enhanced the visual aspects of the games.
This will be achieved by using Threes JS
#### Expanding Browser Compatibility
Add support to for additional web browser(Firefox)


## Screenshots
![IndexTop](https://github.com/m-juin/Transcendence/assets/108357857/15550353-07ec-429c-96db-767b5d092af6)
*Homepage*

![RegisterPage](https://github.com/m-juin/Transcendence/assets/108357857/3fca1368-d6de-4e26-904d-7b7af8c8f9df)
*Registration Page*

![games](https://github.com/m-juin/Transcendence/assets/108357857/b14e8f93-3d0a-4f29-b436-4f5266e908b7)
*Game selection Page*

![TournamentPage2](https://github.com/m-juin/Transcendence/assets/108357857/12b4ef43-021f-4531-bbbd-ea2b4b6e8c08)
*Tournament Page*

![Pong](https://github.com/m-juin/Transcendence/assets/108357857/0d51c5c8-dda8-4342-9e47-49b0c86d7116)
*Pong game*

![Battleship2](https://github.com/m-juin/Transcendence/assets/108357857/618d4d37-accf-49c4-8a3f-af7f4718cc1f)
*Battleship Game*

![UserManagement](https://github.com/m-juin/Transcendence/assets/108357857/0c2437f2-f21b-4431-beb0-7237c37e1aab)
*User settings page*

![2FAQR](https://github.com/m-juin/Transcendence/assets/108357857/dc72c8a5-df57-4b5f-b3cc-da16e088cccb)
*Two-Factor Authentication activation*

![DAshboardPong](https://github.com/m-juin/Transcendence/assets/108357857/67c66434-74b6-47eb-913b-6f8e3b920df5)
*User Dashboard Page*
    
## Made by
    
<table align='center'>
    <tr>
        <td width=200px>
            <a href="https://github.com/mjuin"><img src='https://avatars.githubusercontent.com/u/114703612?s=48&v=4' width=100px></a>
            <h2>mjuin</h2>
            <p>Backend</p>
        </td>
        <td width=200px>
            <a href="https://github.com/GreenPG"><img src='https://avatars.githubusercontent.com/u/108357857?s=400&v=4' width="100px"></a>
            <h2>gpasquet</h2>
            <p>Frontend and chat</p>
        </td>
        <td width=200px>
            <a href="https://github.com/polar-42"><img src='https://avatars.githubusercontent.com/u/116669579?s=48&v=4' width=100px></a>
            <h2>fle-tolg</h2>
            <p>Backend and Blockchain</p>
        </td>
        <td width=200px>
            <a href="https://github.com/TheEmperorPenguin"><img src='https://avatars.githubusercontent.com/u/88889959?s=64&v=4' width=100px></a>
            <h2>gtouzali</h2>
            <p>3D games</p>
        </td>
    </tr>    
</table>
