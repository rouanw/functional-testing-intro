# Functional testing

---

## What?

* Test the application from a consumer's perspective
* Requires application to be deployed as it would be
* Hits all layers of the application

---

## Why?

* Document the functionality of the application
* Prevent anyone from accidentally breaking existing functionality
* Provides confidence that the application does what it's meant to

---

## How?

* Tool to describe functionality (we're using Cucumber)
* A way to call the functionality (we're using Spring's REST template)
* Assertions to verify the functionality (we're using hamcrest)
