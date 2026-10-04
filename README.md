# Cat Wellness Checker (Vet Practice App)

Built for the bootcamp's "complex API" project: an app for a veterinary practice that chains API calls together.

![Cat Wellness Checker screenshot](screenshot.jpg)

Search a cat breed and it pulls the breed profile first (average weight, life span), then uses the breed id from that response to fetch a photo, then grabs the health info like heart rate and normal temperature. Each call waits on the one before it, which is the entire point of the exercise.

TheCatAPI, vanilla JavaScript.
