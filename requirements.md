# Backend Feature Specifications

## 1. User Authentication

### User Endpoint

- POST /api/register
- POST /api/login

### User Input

- Email, password

### User Output

- Success message, JWT token

### User Validation

- Email format, password length

---

## 2. Property Management

### Property Endpoint

- POST /api/properties
- PUT /api/properties/:id
- DELETE /api/properties/:id

### Property Input

- Title, description, location, price

### Property Output

- Success message, property ID

### Property Validation

- Required fields, price format

---

## 3. Booking System

### Booking Endpoint

- POST /api/bookings
- DELETE /api/bookings/:id

### Booking Input

- Property ID, start_date, end_date

### Booking Output

- Booking confirmation

### Constraints

- No overlapping bookings
- Date range must be valid
