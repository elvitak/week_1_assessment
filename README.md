var = "variable"
var.class #string
4.class #number integer
4.2.class #float number
[].class # array
:key.class #symbol
true_class #boolean
{}.class #hash

Tesla = {wheels: 5, max_speed: "1000kph", color: "black"}

Audi = {wheels: 4, max_speed: "180kph", color: "purple"}

array = []

array.push(Tesla)
array.push(Audi)
[{:wheels=>5, :max_speed=>"1000kph", :color=>"black"}, {:wheels=>4, :max_speed=>"180kph", :color=>"purple"}]
how to access 2nd cars color in array:
array[1][:color]
