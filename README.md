# base33hh
Finding the Most Gas-Efficient Sender
best = min(block.transactions, key=lambda x: x["gas"])
print("Lowest gas sender:", best["from"])
