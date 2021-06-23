# Sarcasm_Target_NEE_S2S

Toy model for Sequence-2-sequence Encoder-Decoder units for "Target Sarcasm prediction" from given sentences.

### Sample Output :

> if they can t afford to be poor in wi maybe they ll all move to mn or il and it will help our state in the long run <br>
= it will help our state<br>
* Prediction >>  it will help our state <EOS><br>
Match ratio = 0.0


> if having red hot blind hatred for a year old woman that i ve never met and don t know at all is wrong i don t wanna be right <br>
= outside<br>
* Prediction >>  outside <EOS><br>
Match ratio = 0.0


> oh ye plz take care of the special snowflakes in this world that want to use a linux pc as gaming pc its soooo important <br>
= special snowflakes in this world that want to use a linux pc as gaming pc<br>
* Prediction >>  special snowflakes in this world that want to use a linux pc as gaming pc <EOS><br>
Match ratio = 0.02247191011235955


> if we want to make a bad tactical decision we should be able too i want a x scope on my mac why can t i have it <br>
= want a x scope on my mac<br>
* Prediction >>  want a x scope on my mac <EOS><br>
Match ratio = 0.14747191011235955
  
##### DIS-Similarity ratio = 0.009542601100850655
