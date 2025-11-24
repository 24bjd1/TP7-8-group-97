Create 3 activities that satisfy criteria (e.g., attractions, restaurants, parks).  
Each activity includes type, estimated duration, cost range, and distance.
Activities should be compatible with basic user constraints (budget, dietary, mobility, pace).

Use a simple loop to build days:

for each day:
    if lodging info missing → assume central location
    if no valid activity found → insert fallback (e.g., rest, local walk, free landmark)
    if budget ≤ 0 → include free/low-cost options (parks, public sites)
    if trip length = 1 day → ensure variety across slots
    if trip length ≥ 7 days → avoid repeating same activity type more than twice
    pick Morning activity (near lodging)  
    pick Midday activity (close by)  
    pick Afternoon activity (different theme)  
    pick Evening restaurant or optional event
