[**English**](README.md) | [Українська](README.uk.md)

# Python - Functions Practice

Three short exercises practicing Python functions, dates, randomness, and dict/list comprehensions.

## Stack

- Python 3.12 (standard library only)

## Exercises

### `hw3_1.py` - days from today

`get_days_from_today(date_str)` parses a `YYYY-MM-DD` string and returns the integer number of days between that date and today. Negative values mean a future date; `None` is returned (with a printed message) on bad input.

### `hw3_2.py` - lottery numbers

`get_numbers_ticket(min_, max_, quantity)` returns `quantity` unique numbers in `[min_, max_]`, sorted ascending. Returns an empty list with a printed message if the inputs are out of bounds (`min_ < 1`, `max_ > 1000`, etc.).

```python
print(get_numbers_ticket(10, 14, 5))   # [10, 11, 12, 13, 14]
print(get_numbers_ticket(1, 10, 10))   # [1, 2, ..., 10]
```

### `hw3_4.py` - upcoming birthdays

`get_upcoming_birthdays(users)` takes a list like:

```python
[{"name": "John", "birthday": "1990.07.15"}, ...]
```

…and returns those with a birthday in the next 7 days, with the congratulation date rolled forward to Monday if it lands on a weekend.

## Run

```bash
python hw3_1.py
python hw3_2.py
python hw3_4.py
```
