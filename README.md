# Function111
def compute_discount(quantity, price, discount_rate):
    discount_amount = quantity * price * discount_rate
    discounted_price = quantity * price - discount_amount
    return discount_amount, discounted_price

quantity = float(input("Enter quantity: "))
price = float(input("Enter price: "))
discount_rate = float(input("Enter discount rate (in decimal): "))

discount_amount, discounted_price = compute_discount(quantity, price, discount_rate)

print(f"Quantity: {quantity}")
print(f"Price: {price}")
print(f"Discount Amount: {discount_amount}")
print(f"Discounted Price: {discounted_price}")
