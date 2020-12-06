### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
    if card.value = 1:
  # This should be a double equals to check for equivalence rather than re-assigning
      return True
    else
  # There should be a colon after the 'else'
      return False
   

  dif highest_card(self, card1 card2):
  # This should be 'def' not 'dif' and there should also be a comma between 'card1' and 'card2'
  if card1.value > card2.value:
    return card
  # This should be 'card1' not 'card'
  # There should also possibly be an elif statement for if cards are equal
  else:
    return card2
  


def cards_total(self, cards):
  total
  # This should be 'total = 0'
  for card in cards:
    total += card.value
    return "You have a total of" + total
  
```
