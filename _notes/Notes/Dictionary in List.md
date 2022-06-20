```py
# Which line of code will print "**Steak**"?

1.  order = {
2.      "starter": {1: "Salad", 2: "Soup"},
3.      "main": {1: ["Burger", "Fries"], 2: ["Steak"]},
4.      "dessert": {1: ["Ice Cream"], 2: []},
5.  }
```
![[Pasted image 20220606171455.png]]


___

```py
travel_log = [
{
  "country": "France",
  "visits": 12,
  "cities": ["Paris", "Lille", "Dijon"]
},
{
  "country": "Germany",
  "visits": 5,
  "cities": ["Berlin", "Hamburg", "Stuttgart"]
},
]
#🚨 Do NOT change the code above

#TODO: Write the function that will allow new countries
#to be added to the travel_log. 👇

new_dict = {}

 

def add_new_country(country_name, visits, city_list):
  new_dict["country"] = country_name
  new_dict["visits"] = visits
  new_dict["cities"] = city_list
  travel_log.append(new_dict)



#🚨 Do not change the code below
  
add_new_country("Russia", 2, ["Moscow", "Saint Petersburg"])
print(travel_log)



```