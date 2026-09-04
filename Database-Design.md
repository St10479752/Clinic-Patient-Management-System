# Database Design

## Purpose

The database is designed to store and manage information required by the clinic patient management system.

## Main Entities

- Patient
- Appointment
- Doctor
- Department

## Patient

Stores patient details such as patient ID, name, contact information and patient category.

## Appointment

Stores appointment information including appointment ID, patient, doctor, date, time and appointment status.

## Doctor

Stores doctor information used when managing appointments and patient care.

## Relationships

A patient can have an appointment, while an appointment is associated with a doctor. The database relationships are represented in the ERD located in the `/docs` folder.
