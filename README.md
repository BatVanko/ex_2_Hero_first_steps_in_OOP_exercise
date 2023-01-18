# ex_2_Hero_first_steps_in_OOP_exercise

Create a class called Hero. Upon initialization, it should receive a name (string) and health (number). Create two additional methods:
•	defend(damage) - reduce the given damage from the hero's health:
o	if the health become 0 or less, set it to 0 and return "{name} was defeated"
•	heal(amount) - increase the health of the hero with the given amount

Examples

hero = Hero("Peter", 100)
print(hero.defend(50))
hero.heal(50)
print(hero.defend(99))
print(hero.defend(1))

Output

None
None
Peter was defeated
