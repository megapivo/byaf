words = open("russian_nouns.txt", "r").read().split("\n")
slovo = #рандомное слово
shifr = len(a) * '_ ' #зашифровоное слово
while shifr != slovo:
    bukva = input()
    if len(bukva) > 1:
        bukva = bukva[0]
#проверка на дурака
    if bukva in slovo:
        shifr
