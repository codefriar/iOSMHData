# What is this?

This repo contains the metadata needed to define a solution org for the iOS Mini Hacks Trailhead content.

Due to the nature of the challenges, and the fact that the challenges themselves should delete all records, this repo is setup to provide scripts and data to allow a challenge developer to 'restore' the solution org to a known state before executing the challenge.

# How do I use this?

> All the following steps assume that you've cloned this repository, and have used the command line to authenticate to the solution org using the credentials in the google doc.

Please note. These data files only provide the necessary iosMiniHack1**instrumentation**c recods.

## To reset org to step 1.

No reset needed, as challenge is checking for the presense of a managed package, and the ability to create a record of type `iosMiniHack1__instrumentation__c`

## To reset org to step 2.

Using anonymous apex, execute the following apex statement:

`delete [Select id from iosminihack1__instrumentation__c];`

At the root of this project, use the SFDC command line to run this command

`sfdx force:data:tree:import -f ./data/Step2Data.json`

## To reset org to step 3.

Using anonymous apex, execute the following apex statement:

`delete [Select id from iosminihack1__instrumentation__c];`

At the root of this project, use the SFDC command line to run this command

`sfdx force:data:tree:import -f ./data/Step3Data.json`

## To reset org to step 4.

Using anonymous apex, execute the following apex statement:

`delete [Select id from iosminihack1__instrumentation__c];`

At the root of this project, use the SFDC command line to run this command

`sfdx force:data:tree:import -f ./data/Step4Data.json`

## To reset org to step 5.

Using anonymous apex, execute the following apex statement:

`delete [Select id from iosminihack1__instrumentation__c];`

At the root of this project, use the SFDC command line to run this command

`sfdx force:data:tree:import -f ./data/Step5Data.json`

## To reset org to step 6.

Using anonymous apex, execute the following apex statement:

`delete [Select id from iosminihack1__instrumentation__c];`

At the root of this project, use the SFDC command line to run this command

`sfdx force:data:tree:import -f ./data/Step6Data.json`

## To reset org to step 7.

Using anonymous apex, execute the following apex statement:

`delete [Select id from iosminihack1__instrumentation__c];`

At the root of this project, use the SFDC command line to run this command

`sfdx force:data:tree:import -f ./data/Step7Data.json`
