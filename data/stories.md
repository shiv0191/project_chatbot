<!-- version: "3.1"

stories: -->

## happy path
<!-- steps: -->
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
<!-- steps: -->
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
  <!-- steps: -->
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## greet and check weather
* greet
  - utter_greet
* check_weather
  - utter_check_weather
* goodbye
  - utter_goodbye

## just check weather
* check_weather
  - utter_check_weather
* goodbye
  - utter_goodbye

