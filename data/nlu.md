## intent:greet
- hey
- hello
- hi
- good morning
- good evening
- hey there
- how are you
- talk to AH
- hello I have a question
- dear AH
- dear appie
- hi AH
- hi Appie

## intent:goodbye
- bye
- goodbye
- good bye
- see you around
- see you later
- have a nice day
- thank you
- thanks
- thanks will do
- thank you for the support
- thank you for the explanation
- thank you for the help
- thank you very much
- bye bye
- thnx
- thx
- have a nice weekend
- have a good night
- have a good day
- i'll try tomorrow
- i'll give it a try tomorrow
- you too
- i've already found it

## intent:complain_about_discount
- I did not receive the [bonus]{"entity": "discount", "value": "bonus"}
- I didn't get the [bonus discount]{"entity": "discount", "value": "bonus"}
- We did not receive the [discount]{"entity": "discount", "value": "bonus"}
- the [bonus benefits]{"entity": "discount", "value": "bonus"} has been calculated incorrectly
- the [bonus discount]{"entity": "discount", "value": "bonus"} hasn't been applied
- the [bonus amount]{"entity": "discount", "value": "bonus"} is wrong
- the [bonus reward]{"entity": "discount", "value": "bonus"} was incorrect
- the [bonus reward]{"entity": "discount", "value": "bonus"} hasn't been applied
- the [bonus special]{"entity": "discount", "value": "bonus"} is too low
- the [bonus]{"entity": "discount", "value": "bonus"} has been forgotten
- no [bonus discount]{"entity": "discount", "value": "bonus"} has been applied
- the [discount]{"entity": "discount", "value": "bonus"} is missing
- i'm missing the [bonus rewards]{"entity": "discount", "value": "bonus"}
- we're missing the [bonus rewards]{"entity": "discount", "value": "bonus"}
- [AH]{"entity": "organization", "value":"AH"} didn't give us the [bonus discount]{"entity": "discount", "value": "bonus"}
- [appie]{"entity": "organization", "value":"AH"} has given us too little [bonus]{"entity": "discount", "value": "bonus"}
- you have forgotten my [bonus rewards]{"entity": "discount", "value": "bonus"}
- you have forgotten to apply my [bonus rewards]{"entity": "discount", "value": "bonus"}
 

## intent:bot_challenge
- are you a bot?
- are you a human?
- am I talking to a bot?
- am I talking to a human?
- who are you?
- what are you?
- who is this?

## intent:affirm
- it does
- yes
- yes, thank you
- yep
- yup

## intent:deny
- no
- not really
- nope
- that's not what I asked
- that's not what I meant
- that does not make sense
- that's not helpful

## intent:check_refund_status
- When will I get my money back?
- How will my complaint be settled?
- How is the complaint about our online order refunded?
- When will I get a refund?
- What about the refund for my [coffee](product)?
- Will I still get my damaged packs of [coffee](product) back?
- Where can I find the compensation of my complaint?
- Where can we find the settlement?
- How will you arrange the refund?
- I'd like a refund for my missing products?
- Can you refund the items that haven't been delivered?

## intent:ask_how_to_return_items_with_deposit        
- How do I return a [crate](deposit_item)?
- I'd like to return my [blue crates](deposit_item)
- I want to hand in my [crates](deposit_item)
- I want to get my deposit back
- I still have a number [empty crate](deposit_item) that I'd like to return
- How about my deposit?
- I want get my deposit back
- Where can I return empty beer [crates](deposit_item)?
- Can I return [empty bottles](deposit_item) with the delivery guy?
- Can I return a deposit with the delivery guy?
- How does it work with a deposit for a [crate](deposit_item)?
- Are returnable [bottles](deposit_item) taken by the deliverer?

## intent: inform
- [August 31st]{"entity": "refund_amount", "value": "€ 6,45"}
- [31 August]{"entity": "refund_amount", "value": "€ 6,45"}
- [31 Aug]{"entity": "refund_amount", "value": "€ 6,45"}
- [Aug 31]{"entity": "refund_amount", "value": "€ 6,45"}
- [September 6th]{"entity": "refund_amount", "value": "€ 4,00"}
- [September 6]{"entity": "refund_amount", "value": "€ 4,00"}
- [6 September]{"entity": "refund_amount", "value": "€ 4,00"}
- [6 Sept]{"entity": "refund_amount", "value": "€ 4,00"}
