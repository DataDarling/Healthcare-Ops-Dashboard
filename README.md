# Healthcare Operations: Patient Access & Appointment Utilization
Executive Summary:
This project analyzes a dataset of 110,000+ medical appointments to identify the operational drivers behind patient "no-shows." By developing an interactive Tableau dashboard, I uncovered critical bottlenecks in scheduling lead times and demographic-specific behaviors, providing hospital leadership with actionable insights to improve clinical capacity and reduce revenue leakage.


# The Challenge (Situation/Task):
Hospital "no-shows" represent a significant loss in provider productivity and patient access. The goal was to identify why 20.2% of appointments were being missed and to determine which operational levers (scheduling, reminders, or location) could be adjusted to improve show rates.


# The Solution (Action):

Data Engineering: Cleaned and transformed raw scheduling data in Tableau, correcting documentation errors in date fields and calculating "Lead Time" (wait time) metrics.

Operational Analysis: Developed categorical bins for wait times to identify the "cliff" where patient forgetfulness spikes.

Demographic Profiling: Segmented no-show rates by age cohorts and gender to identify high-risk populations (specifically the 19-35 age group).

Geospatial Insights: Filtered and sorted 80+ neighborhoods to pinpoint specific clinics requiring localized intervention.

Advanced Visualization: Utilized logarithmic trend lines and heatmaps to visualize the correlation between wait times and weekend-adjacent scheduling risks.


# Key Insights (Result):

The 7-Day Cliff: No-show rates quadruple (from 4.6% to 24.1%) the moment a patient has to wait more than 7 days for an appointment.

The Weekend Risk: Friday and Saturday appointments show a 15-20% higher no-show risk compared to mid-week slots.

The SMS Paradox: SMS recipients showed higher no-show rates, indicating that current reminder strategies may be reactive (targeting high-risk, long-lead appointments) rather than preventative.
