# Movie-Ticket-Booking-Calculator
Creating a movie ticket booking calculator

# Movie Ticket Calculator

A Python-based movie ticket pricing system that calculates ticket costs based on user eligibility, discounts, and show preferences.

## Features

- **Age Verification**: Validates user eligibility for ticket booking and evening shows
- **Membership Discounts**: Applies discount for members
- **Seat Type Selection**: Supports different seating categories (Gold, Silver, etc.)
- **Show Time Options**: Different pricing for matinee vs evening shows
- **Weekend Pricing**: Framework for weekend surcharge calculation

## How It Works

The system evaluates multiple criteria:

1. **Minimum Age**: Users must be over 17 to book tickets
2. **Evening Shows**: Restricted to users 21 and older
3. **Membership Status**: Members receive a $3 discount
4. **Weekend Pricing**: Variable pricing based on day of week

## Usage

Set your booking parameters:
```python
