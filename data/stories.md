## greetings
* greet
  - utter_introduction_greet
  - utter_introduction_instructions
  - utter_introduction_how_can_i_help

## complain-about-discount, in store
* complain_about_discount
  - utter_did_you_buy_it_in_a_store
* affirm
  - utter_go_to_service_desk_in_store
> standard_reprompt

## complain-about-discount, online order
* complain_about_discount
  - utter_did_you_buy_it_in_a_store
* deny
> handover

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## reprompt with confirmation
> standard_reprompt
  - utter_did_that_help
* affirm
  - utter_great_that_it_helped
  - utter_goodbye
  
## reprompt - not helped
> standard_reprompt
  - utter_did_that_help
* deny
> handover

## handover
> handover
  - utter_handover
  - utter_goodbye
