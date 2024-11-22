zad 1:
Person.objects.all()

zad 2:
Person.objects.filter(name__startswith="k")

zad 3:
Person.objects.filter(name__startswith="k").values()

zad 4: