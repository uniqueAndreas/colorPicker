# colorPicker
Omnis Studio Color Picker for remote forms

You can use the color picker in two ways:

1. use it as a subform component or
2. use it as a subform set remote form

There needs to be a public method $setColor in the main form that 
receives a parameter of type Integer (32bit) that is the color
chosen by the color picker. 

The color picker uses $cinst.$container().$setColor() in order
to set the color in the underlying form. Works for subform as well
as a subform set.

Have fun!

Andreas
