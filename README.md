# Doing some Kotlin stuff and more
Following the Kotlin bootcamp @ https://codelabs.developers.google.com/codelabs

#Some Notes
Can't reassign Val but you can reassign var
var fish = 1
fish = 2
val acuario = 1
acuario = 2
error: val cannot be reassigned

#You can create string templates by using $variable into the string, the $variable name is replaced with the text/value
#like this
val pescados = 5
val plantas = 12
"Tengo $pescados pescados en mi pecera " + "y $plantas plantas en mi casa"
res3: kotlin.String = Tengo 5 pescados en mi pecera y 12 plantas en mi casa

#or this
"Tengo ${pescados + plantas } pescados y plantas en mi casa"
res5: kotlin.String = Tengo 17 pescados y plantas en mi casa
