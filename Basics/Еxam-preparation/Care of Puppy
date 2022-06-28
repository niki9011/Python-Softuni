kg_food = int(input()) * 1000
gram_eaten = 0
command = 0

while command != "Adopted":
    command = input()

    if command == "Adopted":
        if kg_food >= gram_eaten:
            print(f"Food is enough! Leftovers: {kg_food - gram_eaten} grams." )
        else:
            print(f"Food is not enough. You need {abs(gram_eaten - kg_food)} grams more.")
        break

    gram_eaten += int(command)

