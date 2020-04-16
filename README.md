![Octo](/Octo.png)
# Octo
Octo is a simple discord bot for submitting and removing github issues through discord using the github API.


## Installation
1. clone this repository:
```
cd folder/to/clone-into/
git clone https://github.com/DoctorPepe/Octo
```
2. create a new application through the discord developer portal
3. copy the private token into the correct field in main.py
4. run:
```
cd folder/of/local/repository/
python3 main.py
```


## Usage

### Owner
#### !symbolic
Creates a symbolic link and webhook to a new repository
```
!symbolic "https://github.com/link/to/repository"
```
#### !removeSymbolic
removes a linked repository and destroys the webhook
```
!removeSymbolic "repository-name"
```


### User
#### !submit
Submits a new issue to the target repository
```
!submit "target" "title" "body" "tags, tags"
!submit "target" "title"
```
#### !remove
