# ALX Travel App - Chapa Payment Integration

## Payment Integration Features
- Chapa API integration for payment processing
- Secure payment initiation and verification
- Payment status tracking
- Error handling

## API Endpoints
- `POST /api/payments/initiate/<booking_id>/` - Initiate payment
- `POST /api/payments/verify/<booking_id>/` - Verify payment
- `GET /api/payments/status/<booking_id>/` - Check status

## Setup
1. Install requirements: `pip install -r requirements.txt`
2. Set environment variables in `.env`
3. Run migrations: `python manage.py migrate`
4. Start server: `python manage.py runserver`
