# 📈 Stock Picker

This is a simple Ruby script that solves a classic problem from [The Odin Project](https://www.theodinproject.com/):  
**"When should I buy and sell a stock to make the most money?"**

---

## 🧠 Project Description

The `stock_picker` method takes an array of stock prices — one for each day — and tells you the best **day to buy** and the best **day to sell** to make the most profit. Days start at index `0`.

It assumes:
- You can **only buy once** and **sell once**
- You **must sell after you buy**

---

## 🛠️ How It Works

1. Loops through the array of prices.
2. Remembers the **lowest price seen so far** (best day to buy).
3. Calculates how much money you would make if you sold today.
4. Keeps track of the **maximum profit** and the **best days** to buy and sell.

---

## 📦 Example

```ruby
stock_picker([17, 3, 6, 9, 15, 8, 6, 1, 10])
# => [1, 4]
