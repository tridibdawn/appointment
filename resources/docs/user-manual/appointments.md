# Appointments
---
- [Description](/{{route}}/{{version}}/apointments/#description)
- [Book Appointment](/{{route}}/{{version}}/apointments/#book-appointment)
- [View History](/{{route}}/{{version}}/apointments/#view-history)
- [Generate Report](/{{route}}/{{version}}/apointments/#generate-report)

<a name="description"></a>
## Description

`Appointment` booking option can be accessed by `admin`, `employee` and `customer`. Any authenticated user can book an `appointment` with available `slots`. `Appointment` module consists of `book appointment`, `view history` and `generate report` options. Out of these options only `book appointment` option is available for every `authenticated user`. Other two options `view history` and `generate report` can be accessed by `admin` and `employee` only.


<a name="book-appointment"></a>
## Book Appointment

`Book Appointment` is available for every `authenticated user`. Here user can select a `service` and `slots` will appear with respect that `service` in `card format`, if available. On selecting available card `slot details` will be displayed. `User` can choose available in date picker and time and `book` an appointment. The structure of `book appointment` form is as follows,


| # |       Field      |     Type   |
| : |         :        |       :    |
| 1 |  Select Service  |   Dropdown |
| 2 |     Providers    |     Card   |
| 3 |        Day       |   Readonly |
| 4 |       From       |   Readonly |
| 5 | Service Duration |   Readonly |
| 6 |       Price      |   Readonly |
| 7 |       Date       | Datepicker |
| 8 |     Start Time   | Timepicker |


<a name="view-history"></a>
## View History

`View History` option can be visited by `admin` and `employee`. Here one indivisual with proper permissions can visit report of any individual customer bookings. Details of fields of the report are as follows,

| # |   Fields   |
| : |      :     |
| 1 |   Services |
| 2 |  Employees |
| 3 |    Price   |
| 4 |     Date   |
| 5 | Start Time |
| 6 |   Duration |
| 7 |  Booked By |

<a name="generate-report"></a>
## Generate Report

`Generate Report` can be accessed by `admin` and `employees`. This report is generated with respect to different time period by date range picker. The report can be generated by the following options,

- Today
- Yesterday
- Last 7 days
- Last Week (Mo-Su)
- Month to Date
- Previous Month
- Year to Date

After this, a report table will be generated for view. The table consists of the following fields,

| # |   Fields   |
| : |      :     |
| 1 |   Services |
| 2 |  Employees |
| 3 |    Price   |
| 4 |     Date   |
| 5 | Start Time |
| 6 |   Duration |
| 7 |  Booked By |