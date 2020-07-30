## Greeting story
* greet
    - utter_greet

## happy path
* inform
    - train_booking_form
    - form{"name": "train_booking_form"}
    - form{"name": null}
* affirm
    - utter_slots_values

## happy path
* inform{"from": "delhi"}
    - train_booking_form
    - form{"name": "train_booking_form"}
    - form{"name": null}
* affirm
    - utter_slots_values

## happy path
* inform{"to": "mumbai"}
    - train_booking_form
    - form{"name": "train_booking_form"}
    - form{"name": null}
* affirm
    - utter_slots_values

## happy path
* inform{"time": "Tuesday"}
    - train_booking_form
    - form{"name": "train_booking_form"}
    - form{"name": null}
* affirm
    - utter_slots_values

## happy path
* inform{"from": "delhi", "to": "delhi"}
    - train_booking_form
    - form{"name": "train_booking_form"}
    - form{"name": null}
* affirm
    - utter_slots_values

## happy path
* inform{"from": "delhi", "time": "Tuesday"}
    - train_booking_form
    - form{"name": "train_booking_form"}
    - form{"name": null}
* affirm
    - utter_slots_values

## happy path
* inform{"to": "delhi", "time": "Tuesday"}
    - train_booking_form
    - form{"name": "train_booking_form"}
    - form{"name": null}
* affirm
    - utter_slots_values

## happy path
* inform{"from": "delhi", "to": "delhi", "time": "Tuesday"}
    - train_booking_form
    - form{"name": "train_booking_form"}
    - form{"name": null}
* affirm
    - utter_slots_values