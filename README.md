import numexpr
from colorama import init, Fore
init()

print(Fore.YELLOW)

expr = input("Введите математическое выражение: ")
resultat = numexpr.evaluate(expr)

print(Fore.GREEN)
print(f"Результат: {resultat}")
