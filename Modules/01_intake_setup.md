> Change log (2025-11-16):
> - Update detail criteria to support data accuracy

Collect essential details:

- Destination(s) (List of strings)
- Dates or trip length (Dates in ISO 8601: YYYY-MM-DD | Trip length as an integer)
- Number of travelers (Integer only)
- Budget style (affordable, mid-range, luxury)
- Interests (food, culture, nature, etc.)
- Preferred pace (relaxed, balanced, fast)
- Key constraints (mobility, weather, diet)

Normalize details (e.g., dates, season) and store them in a simple JSON internally.
