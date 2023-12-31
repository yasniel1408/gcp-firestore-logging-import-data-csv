npm install @google-cloud/firestore

npm install @google-cloud/logging


# Comando para crear data de prueba en csv
node createTestData 1000

# Comando para crear la data en base de datos
node importTestData customers_1000.csv

# Pet Theory

Twelve years ago, Lily started the Pet Theory chain of veterinary clinics. The Pet Theory chain has expanded rapidly over the last few years. Their old appointment scheduling system is not able to handle the increased load, so Lily is asking you to build a Google Cloud Platform system that scales better than the legacy solution.

Welcome to the Pet Theory Quest.

## Author: 
Martin Omander

## Architecture

![GSP642: Migrating Data to a Firestore Database](https://cdn.qwiklabs.com/Yfo0T7MHSB8V2VwDmVYNMJQo5bly1%2BtEbv%2FBrpUNbZ8%3D)

## Description: 

Qwiklabs Quest based on the presentation "Pet Theory"

[GSP642 Lab 01 - Migrating to a Firestore database](https://google.qwiklabs.com/catalog_lab/2163)

Pet Theory have a legacy database and they want to move this to Firestore. Can you help them migrate their data by setting up a new database and populating it with customer data?

In this lab you will be tasked with the following activities:

* Create a Firestore database
* Create a comma separated values (CSV) file for the purpose of testing the database load process
* Repurpose an NodeJS application to Upload the CSV test data to the Firestore database
* Specify role permissions for the development team
