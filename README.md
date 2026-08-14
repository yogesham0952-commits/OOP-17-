# OOP-17-
class Factorial:

    def calculate(self, n):
        # Base condition
        if n == 0 or n == 1:
            return 1

        return n * self.calculate(n - 1)


obj = Factorial()

number = 5
result = obj.calculate(number)

print("Factorial =", result)
