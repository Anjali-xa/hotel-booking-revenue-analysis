# Hotel Booking and Revenue KPI Guide

## KPI definitions
| KPI | Definition | Notes |
|---|---|---|
| Occupancy rate | Occupied room-nights / available room-nights | Exclude out-of-order rooms consistently |
| ADR | Room revenue / rooms sold | State tax and fee treatment |
| RevPAR | Room revenue / available room-nights | Align room revenue scope with ADR |
| Cancellation rate | Cancelled bookings / bookings made | Define cohort by booking date |
| Lead time | Arrival date - booking date | Validate date order |

## Data checks
- Identify duplicate booking IDs.
- Validate arrival and booking dates.
- Separate cancelled, no-show, and completed stays.
- Check room-night calculations across multi-night stays.
- Standardise currencies and tax treatment.
- Document whether complimentary rooms count as occupied.

## Questions
1. How do ADR and RevPAR vary by season?
2. Which booking channels have higher cancellation rates?
3. How does lead time vary by customer segment?
4. What is the relationship between occupancy and room pricing?

## Caveats
Revenue comparisons need consistent treatment of taxes, fees, refunds, and currency conversion.