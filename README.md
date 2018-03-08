# RPS Challenge - Week 3 - Makers Academy

This is an individual challenge. The task is to provide a _Rock, Paper, Scissors_ game for Marketeers so they can play on the web.  

I developed this in Ruby, with Sinatra framework, as this was the focus of our learning at that point in the course.  


## Basic Rules

- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock

## User Stories:

```
As a marketeer
So that I can see my name in lights
I would like to register my name before playing an online game

As a marketeer
So that I can enjoy myself away from the daily grind
I would like to be able to play rock/paper/scissors  
```

## Getting started

##### You can visit my Rock, Paper, Scissors app at: https://rps-attyc.herokuapp.com/

![image](https://user-images.githubusercontent.com/11736479/37111713-50bc5a68-2238-11e8-9e3b-60d42934dbb5.png)    

---  

##### If you'd rather look at the code, please do the following:

Clone the repository:
```
git clone https://github.com/AttyC/rps-challenge
```
Run the following command to install dependencies:
```
bundle install
```

## Usage
To run the app, start the local server:  

```
rackup
```
Navigate to http://localhost:9292


## Running tests
**RSpec** - unit tests for individual methods  
**Capybara** - feature tests for simulated 'user' testing in the browser

To run RSpec and Capybara tests:
```
rspec
```

## Functionality
- two marketeers can play against each other
- each marketeer should be able to enter their name before the game
- each marketeer will be presented the choices (rock, paper and scissors)
- each marketeer can choose one option
- a winner will be declared (or a draw)


## Technical info

Ruby version: '2.4.0'

## Gems installed
gem 'capybara'  
gem 'rake'  
gem 'rubocop'  
gem 'rspec'  
gem 'simplecov', require: false  
gem 'simplecov-console', require: false  
gem 'sinatra'  

## Design
 Assistance with choosing fonts and some colours provided by Isla, 8. My own CSS plus fonts from Google Fonts

## If I had more time
I would enable two views so each user is unable to see the other's choice. 
