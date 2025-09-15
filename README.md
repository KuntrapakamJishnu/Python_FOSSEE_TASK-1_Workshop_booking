Workshop Booking – UI/UX Enhancement

This repository contains my improvements to the Workshop Booking website provided by FOSSEE# **Workshop Booking**

> This website is for coordinators to book a workshop(s), they can book a workshop based on instructors posts or can propose a workshop date based on their convenience.


Features
* Statistics
    1. Instructors Only
        * Monthly Workshop Count
        * Instructor/Coordinator Profile stats
        * Upcoming Workshops
        * View/Post comments on Coordinator's Profile
    2. Open to All
        * Workshops taken over Map of India
        * Pie chart based on Total Workshops taken to Type of Workshops.

* Workshop Related Features
    > Instructors can Accept, Reject or Delete workshops based on their preference, also they can postpone a workshop based on coordinators request.

__NOTE__: Check docs/Getting_Started.md for more info.

Setup Instructions

Follow these steps to set up and run the project locally:

Clone the repository
<git clone https://github.com/KuntrapakamJishnu/Python_FOSSEE_TASK-1_workshop_booking.git/>
cd workshop_booking

Create and activate a virtual environment

python -m venv venv
# On Windows
venv\Scripts\activate
# On Mac/Linux
source venv/bin/activate

Install dependencies

pip install -r requirements.txt

##Run database migrations:

python manage.py makemigrations
python manage.py migrate

##Create a superuser (for accessing admin panel)

python manage.py createsuperuser

##Run the development server

python manage.py runserver

Open the site in your browser at:
 http://127.0.0.1:8000/

(Optional) Access the Django Admin Panel at:
 http://127.0.0.1:8000/admin/

Working website images:


<img width="1898" height="884" alt="Screenshot 2025-09-09 203356" src="https://github.com/user-attachments/assets/7d7e769b-d2df-486d-9377-6291d6710888" />

<img width="1869" height="833" alt="Screenshot 2025-09-09 204008" src="https://github.com/user-attachments/assets/87e1e4bc-53dc-4aa4-ad54-63e994911335" />
<img width="1649" height="773" alt="Screenshot 2025-09-09 200850" src="https://github.com/user-attachments/assets/19830a44-932f-467f-9684-bde30eeade54" />
<img width="1817" height="391" alt="Screenshot 2025-09-10 003333" src="https://github.com/user-attachments/assets/5041d5e6-d9b2-4958-8a46-ad6231996ad3" />
<img width="1737" height="888" alt="Screenshot 2025-09-09 200753" src="https://github.com/user-attachments/assets/a73084d1-010d-483b-a5b3-023c05a2cc57" />
<img width="1892" height="780" alt="Screenshot 2025-09-09 193710" src="https://github.com/user-attachments/assets/11ea529f-ab8c-4fe7-a0b1-5a337a2d8bfa" />

Reasoning
1. What design principles guided your improvements?

Mobile-first design: Prioritized small screen readability.

Consistency: Kept a uniform color palette, button styles, and typography.

Clarity: Improved spacing and grouping for readability.

Affordance: Ensured buttons and links look clearly interactive.

2. How did you ensure responsiveness across devices?

Used Bootstrap grid system and media queries.

Tested layout across multiple screen sizes (mobile, tablet, desktop).

Ensured navigation collapses into a hamburger menu on smaller screens.

3. What trade-offs did you make between design and performance?

Chose Bootstrap (slightly larger CSS footprint) for faster development and consistent design patterns.

Avoided heavy animations or large image assets to maintain fast load times.

Kept external dependencies minimal to balance design and performance.

4. What was the most challenging part of the task and how did you approach it?

The main challenge was making the forms intuitive and responsive.

Approach:

Used card layouts to group form elements.

Added proper input spacing, labels, and placeholder hints.

Ensured accessibility with semantic HTML and aria-labels.

Submission

Repository Link: https://github.com/KuntrapakamJishnu/Python_FOSSEE_TASK-1_Workshop_booking
