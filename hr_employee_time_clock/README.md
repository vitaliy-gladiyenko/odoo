# Odoo Employee Time Clock

## Tracking employees' over- and undertime, iOS apps for signing in and leave requests.

Employee Time Clock calculates over- and undertime for each employee and allows employees to sign in or sign out with a mobile app or with a QR code at company's entrance.

### Features
* Timesheet generation
* Import leaves
* One more nice thing
* You tell me

## How it works

The module adds a new data type called "Duty hours", which is the baseline for all calcualtions. Duty hours are calculated based on the time schedule assigned to an employee/contract and therefore can be configured on a daily basis. Whenever an employee gets an approved leave, the Duty Hours for those days are set to 0.

Once you have a time schedule set up for an employee, his working hours are tracked using sign in/out timestamps. Each employee can use one of these methods to sign in/out:
* Sign in/out to your Odoo instance
* Sign in/out from our iPhone app
* Sign in/out at the company's entrance using our QR code scanning iPhone/iPad app

## Timesheet generation
## Import leaves
## Installation notes

# iOS apps

## Odoo time clock (iPad & iPhone)

This app allows your employees to sign in to Odoo using a simple QR code, printed on a card. Free for up to 3 users.

### Features

* Simple sign in process with easy to produce QR codes
* No additional equipment needed (e/m-cards, readers etc.)
* Displays company-wide announcements on sign in
* Allows to quickly order a lunch on sign in (if the Lunch module installed)

Screenshots go here.

### How to make a QR code

In order to sign in with a QR code we suggest you to print small stickers with it, which employees can put on their pass cards, personal devices, inside a wallet or wherever else they are comfortable with.
QR code should have an employee ID in a text format!
Feel free to use online tools for making QR codes - https://www.the-qrcode-generator.com/

### Lunch ordering

If odoo module "Lunch" is installed and lunch items are defined, they are shown after each sign in and a user is allowed to choose his preference. The app can operate in "Lunch order" only mode. App settings:
* Define which categories have to be shown
* "Lunch only" mode: no sign in/out will be recorded. This is useful e.g. for coffee consummation book keeping.
* You can define if the lunch screen only has to be shown for one order per day or of after each sign in.

### Company info message

A company wide information message can be defined as a calender entry, tagged with "Station". The message will be shown for the entry period. The calender entry has to be created with the same user which is used for signing in to the app.
The app checks your calendar every 5 minutes, thus you might need to wait a little bit until next employee sees it upon signing in. Your company logo, if available, is displayed as well.

## Odoo HR (iPhone)

Simple app for signing in/out, tracking personal over- and undertime, requesting leaves.

### Features
* Sign in/out
* Sign in/out history
* Attendance analysis
* Leave requests

Screenshots go here.
