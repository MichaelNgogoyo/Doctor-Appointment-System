## Doctor Appoinmtnt booking
- Personas:
    - patient
    - Doctor
    - Admin
- Booking story
    - Authenticate
    - History of apoinments
    - Create - Notify doctors in that category
      - Time
      - Note
      - Categories
          - with pricing
    - Statuses - Pending, Seen, Approved/Rejected
- Doctor story
    - Authenticate
    - Apointment tabs
        - [New Appointments, History]
        - View Apointment - Mark this apointment as 'seen'
            - Aprove/Reject - Notify patient (Email, and Laravel DB notification)
- Admin stories
    - Authenticate
    View report summary
        - Number of apointments
            - Revenue from appointments
        - Doctor with most apointment
        - Category with most appointments
