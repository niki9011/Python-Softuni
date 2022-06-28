numbers_alumin = int(input())
size = input()
receiving = input()
price = 0

if numbers_alumin >= 10:
    if size == "90X130":
        if 30 >= numbers_alumin > 10:
            price = numbers_alumin * 110
            if receiving == "With delivery":
                price += 60
        elif 60 >= numbers_alumin > 30:
            price = (numbers_alumin * 110) * 0.95
            if receiving == "With delivery":
                price += 60
        elif numbers_alumin > 60:
            price = (numbers_alumin * 110) * 0.92
            if receiving == "With delivery":
                price += 60

    elif size == "100X150":
        if 40 >= numbers_alumin > 10:
            price = numbers_alumin * 140
            if receiving == "With delivery":
                price += 60
        elif 80 >= numbers_alumin > 40:
            price = (numbers_alumin * 140) * 0.94
            if receiving == "With delivery":
                price += 60
        elif numbers_alumin > 80:
            price = (numbers_alumin * 140) * 0.90
            if receiving == "With delivery":
                price += 60

    elif size == "130X180":
        if 20 >= numbers_alumin > 10:
            price = numbers_alumin * 190
            if receiving == "With delivery":
                price += 60
        if 50 >= numbers_alumin > 20:
            price = (numbers_alumin * 190) * 0.93
            if receiving == "With delivery":
                price += 60
        elif numbers_alumin > 50:
            price = (numbers_alumin * 190) * 0.88
            if receiving == "With delivery":
                price += 60

    elif size == "200X300":
        if 25 >= numbers_alumin > 10:
            price = numbers_alumin * 250
            if receiving == "With delivery":
                price += 60
        if 50 >= numbers_alumin > 25:
            price = (numbers_alumin * 250) * 0.91
            if receiving == "With delivery":
                price += 60
        elif numbers_alumin > 50:
            price = (numbers_alumin * 250) * 0.86
            if receiving == "With delivery":
                price += 60

if numbers_alumin > 99:
    price *= 0.96
    print(f"{price:.2f} BGN")
elif numbers_alumin <= 10:
    print(f"Invalid order")
else:
    print(f"{price:.2f} BGN")
