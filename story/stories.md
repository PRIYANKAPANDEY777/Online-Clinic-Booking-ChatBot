## happy path
* greet
  - utter_greet
  - utter_ask_what_can_I_do
* clinic_finder{"location":"Maharashtra"}
  - action_find_address
* thanks
  - utter_Welcome
  - action_slot_reset

## happy path2
* greet
  - utter_greet
  - utter_ask_what_can_I_do
* clinic_finder{"facility":"hospital","location":"Maharashtra"}
  - action_find_address
* thanks
  - utter_Welcome
  - action_slot_reset

## happy path3
* greet
  - utter_greet
  - utter_ask_what_can_I_do
* clinic_finder{"facility":"hospital"}
  - utter_ask_location
* clinic_finder{"location":"Maharashtra"}
  - action_find_address
* thanks
  - utter_Welcome
  - action_slot_reset

## story_goodbye
* goodbye
  - utter_goodbye
  - action_slot_reset

## story_thankyou
* thanks
  - utter_Welcome
  - action_slot_reset

## bot challenge
* bot_challenge
  - utter_iamabot
  - action_slot_reset
