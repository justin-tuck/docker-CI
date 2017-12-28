# Test app for Pluralsight course

This is a quick and dirty test node.js app cobbled together for the purposes of demonstrating a basic CI/CD workflow with Docker Hub for a Pluralsight video training course..

## Instructions for use

All of the files included in the .zip file (available to Plus subscribers) should be unzipped into a new directory.

Initializing a Git repo and making a remote of it on GitHub are explained in Module 2 of the course.

The viewer should have Git installed and have a GitHub account.

## Docker Hub
Link Git Hub account and create and un check automatic build.  Create a trigger and user that url in Circle CI

## Circle CI
Link your Git Hub account and select your project you'll need to create a circle.yml with your project specifications and location of tests and adding the env variable to commands

### TRIGGER VALUE in circle CI
curl -H "Content-Type:application/json" --data '{"build":true}' -X POST <TRIGGER_URL>

Need o make sure that is exact or it will fail

## Docker Cloud

## Amazon Web Services