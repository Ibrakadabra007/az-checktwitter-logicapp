# az-checktwitter-logicapp
This is a ```logicApp``` with several actions. The logicapp triggers (n-times/day) based on a tweet that is spawned - from a *user* - and uses ```cognitive services``` to detect sentiment. If the sentiment score is < than a criteria-constant (0.7), an SMS alerts a recipient about the negative tweet and the the content can be optionally persisted, for auditing.

## NOTE: - ```Twilio``` has changed its pricing model so IOW the SMS workflow will not work unless you pay a minimum (No Sandbox membership available!)
