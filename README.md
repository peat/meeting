# meeting

Calculates the ongoing cost of a meeting, based on the compensation of the participants.

## Usage

Compensation is expressed in thousands per year, for example, a total compensation of $50,000 per year would be "50" with an additional parameter per person.

For example, to calculate the running cost of a meeting with participants who are making $250k, $85k, $150k, and $90k.

```
$ meeting 250 85 150 90
This meeting costs $287.50 per hour.
$0.80
$1.60
...
```

