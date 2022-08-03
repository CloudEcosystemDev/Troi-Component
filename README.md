# <p align="center" width="100%"> <img src="./logo.png" width="250" height="250"> </p> 
# <p align="center" width="100%"> Troi API OIH Connector </p>

## Description

A generated OIH connector for the Troi API API (version 2.0.0).

Generated from: https://{customer}.troi.software/api/v2/rest<br/>
Generated at: 2022-08-03T14:11:30+02:00

## API Description

This is the official API documentation of Troi.<br/>
<br/>
# Authentication<br/>
<br/>
Troi offers basic auth for authentication.<br/>
<br/>
<security-definitions /><br/>

## Authorization

Supported authorization schemes:
- Basic Authentication - Login is via Basic Auth using the Troi credentials. It is important that the password is hashed in advance with md5.

As an example:

username: `troi`

password: `nopass`



On api side:

username: `troi`

password (md5(nopass)): `0945fc9611f55fd0e183fb8b044f1afe`


## Actions

### Fetch Absence for the given Absence ID

*Tags:* `absences`

#### Input Parameters
* `id` - _required_ - Absence id<br/>

### Save Absence object

*Tags:* `absences`

### Update Absence object

*Tags:* `absences`

#### Input Parameters
* `id` - _required_ - Absence id<br/>

### Save account groups object

*Tags:* `accountGroups`

### Fetch Account Group for the given Account Group ID

*Tags:* `accountGroups`

#### Input Parameters
* `id` - _required_ - Account Group id<br/>

### Update Account Groups Object

*Tags:* `accountGroups`

#### Input Parameters
* `id` - _required_ - Account group id<br/>

### Delete Absence Groups

*Tags:* `accountGroups`

#### Input Parameters
* `id` - _required_ - Account Group id<br/>

### Save Accounting Entry Object

*Tags:* `accountingEntries`

### Update Accounting Entry Object

*Tags:* `accountingEntries`

#### Input Parameters
* `id` - _required_ - Accounting entry id<br/>

### Delete Accounting Entry

*Tags:* `accountingEntries`

#### Input Parameters
* `id` - _required_ - Accounting entry id<br/>

### Fetch accounting entry collection for the given accounting entry collection ID

*Tags:* `accountingEntryCollections`

#### Input Parameters
* `id` - _required_ - Accounting entry collection id<br/>

### Save accounting entry collections

*Tags:* `accountingEntryCollections`

### Update accounting entry collection

*Tags:* `accountingEntryCollections`

#### Input Parameters
* `id` - _required_ - Accounting entry collection id<br/>

### Fetch Accounting Entry for the given Accounting Entry ID

*Tags:* `accountingEntries`

#### Input Parameters
* `id` - _required_ - Accounting entry id<br/>

### Delete accounting entry collection

*Tags:* `accountingEntryCollections`

#### Input Parameters
* `id` - _required_ - Accounting entry collection id<br/>

### Delete Account

*Tags:* `accounts`

#### Input Parameters
* `id` - _required_ - Account id<br/>

### Update Account

*Tags:* `accounts`

#### Input Parameters
* `id` - _required_ - Account id<br/>

### Fetch Billing for the given Billing ID

*Tags:* `billing`

#### Input Parameters
* `id` - _required_ - Fetch Billing for the given Billing ID<br/>
* `extendedObject` - _optional_ - extended object contains the full calculation position display path<br/>

### Fetch Booking Year for the given ID

*Tags:* `bookingYear`

#### Input Parameters
* `id` - _required_ - Fetch Billing for the given Billing ID<br/>

### Update Billing

*Tags:* `billing`

#### Input Parameters
* `id` - _required_ - Billing id<br/>

### Delete Billing

*Tags:* `billing`

#### Input Parameters
* `id` - _required_ - Billing id<br/>

### Save Booking Year

*Tags:* `bookingYear`

### Save Billing

*Tags:* `billing`

### Delete calculation position

*Tags:* `calculationPositions`

#### Input Parameters
* `id` - _required_ - Calculation position ID<br/>

### Update Booking Year

*Tags:* `bookingYear`

#### Input Parameters
* `id` - _required_ - Booking Year id<br/>

### Update calculation position

*Tags:* `calculationPositions`

#### Input Parameters
* `id` - _required_ - Calculation position ID<br/>

### Save Calculation Position

*Tags:* `calculationPositions`

### Fetch calendar event for the given calendar event ID

*Tags:* `calendarEvents`

#### Input Parameters
* `id` - _required_ - Fetch calendar event for the given calendar event ID<br/>

### Save calendar event

*Tags:* `calendarEvents`

### Delete calendar event

*Tags:* `calendarEvents`

#### Input Parameters
* `id` - _required_ - Calendar event ID<br/>

### Save project

*Tags:* `projects`

### Update calendar event

*Tags:* `calendarEvents`

#### Input Parameters
* `id` - _required_ - Calendar event ID<br/>

### Save Account

*Tags:* `accounts`

### Update project

*Tags:* `projects`

#### Input Parameters
* `id` - _required_ - Project ID<br/>

### Delete project

*Tags:* `projects`

#### Input Parameters
* `id` - _required_ - Project ID<br/>

### Update calendar event participant

*Tags:* `calendarEventParticipants`

#### Input Parameters
* `id` - _required_ - Calendar event participant ID<br/>

### Fetch Account given Account ID

*Tags:* `accounts`

#### Input Parameters
* `id` - _required_ - Account id<br/>

### Fetch project for the given project ID

*Tags:* `projects`

#### Input Parameters
* `id` - _required_ - Fetch project for the project ID<br/>

### Fetch calendar event participant for the given calendar event participant ID

*Tags:* `calendarEventParticipants`

#### Input Parameters
* `id` - _required_ - Fetch calendar event participant for the given calendar event participant ID<br/>

### Fetch client for the given client ID

*Tags:* `clients`

#### Input Parameters
* `id` - _required_ - Fetch client for the given client ID<br/>

### Delete Booking Year

*Tags:* `bookingYear`

#### Input Parameters
* `id` - _required_ - Booking Year id<br/>

### Fetch calculation position for the given calculation position ID

*Tags:* `calculationPositions`

#### Input Parameters
* `id` - _required_ - Fetch calculation position for the given calculation position ID<br/>

### Delete calendar event participant

*Tags:* `calendarEventParticipants`

#### Input Parameters
* `id` - _required_ - Calendar event participant ID<br/>

### Save contact category

*Tags:* `categories`

### Fetch contact categorie by ID

*Tags:* `categories`

#### Input Parameters
* `id` - _required_ - Fetch contact categorie by ID<br/>

### Delete contact categorie

*Tags:* `categories`

#### Input Parameters
* `id` - _required_ - Contact categorie ID<br/>

### Delete contact

*Tags:* `contacts`

#### Input Parameters
* `id` - _required_ - Contact ID<br/>

### Update contact categorie

*Tags:* `categories`

#### Input Parameters
* `id` - _required_ - Contact categorie ID<br/>

### Fetch contact for the given ID

*Tags:* `contacts`

#### Input Parameters
* `id` - _required_ - Fetch contact for the given ID<br/>

### Save calendar event participants

*Tags:* `calendarEventParticipants`

### Fetch customer for the given customer ID

*Tags:* `customers`

#### Input Parameters
* `id` - _required_ - Fetch customer for the given customer ID<br/>

### Save customer

*Tags:* `customers`

### Update customer

*Tags:* `customers`

#### Input Parameters
* `id` - _required_ - Customer ID<br/>

### Fetch supplier for the given supplier ID

*Tags:* `suppliers`

#### Input Parameters
* `id` - _required_ - Fetch supplier for the given supplier ID<br/>

### Save supplier

*Tags:* `suppliers`

### Update contact

*Tags:* `contacts`

#### Input Parameters
* `id` - _required_ - Contact ID<br/>

### Save contact

*Tags:* `contacts`

### Update supplier

*Tags:* `suppliers`

#### Input Parameters
* `id` - _required_ - Supplier ID<br/>

## License

: Troi<br/>
                    <br/>

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
