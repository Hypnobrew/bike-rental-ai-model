# Electric scooter rental AI model

Final project for the Building AI course

## Summary

In my home town we have dedicated eletrics scooter rental spots all over the city. Sometimes these spots are empty and in other spots they are very crowded. This will be solved with an AI model.

## Background

Very common problem where people cannot get a scooter and sometimes it is hard to leave a scooter since the spot is very crowded.

It does not solve world hunger but a daily to daily problem which could be optimzed.

## How is it used?

It could be used by electric scooter operators from day to day to predict how scooters should be transported to optimize availability. 

Some sort of web tool can be built on top of the AI model, which visualize from which source to destination and how many scooters should be transported.

As always it hard to explain how the model work, so sort of insights should be included.

## Data sources and AI methods

I will use api provided by each electric scooter provider. It can be fetched via a rest API, so the model can with ease be retrained with new continous data.

Example of the data fetch from the api:
```
   "last_updated": 1574954898,
    "ttl": 0,
    "data": {
        "bikes": [
            {
                "bike_id": "0fae06eb-aaaa-0000-cccc-77f696a30000",
                "lat": 48.871983,
                "lon": 2.303089,
                "is_reserved": 1,
                "is_disabled": 0,
            },
            {
                "bike_id": "8c0940ec-aaaa-0000-cccc-3057d9820000",
                "lat": 48.853252,
                "lon": 2.343597,
                "is_reserved": 0,
                "is_disabled": 0,
            }
        ]
    }
}
```

## Challenges

No really ethical considerations since it does not include any humans or data around humans. 

This project only gives a hint how to move scooters rather than a complete solution.

## What next?

Need to verify which machine learning algorithm is suitable for this type of problem. Then figure out how to verify that the suggestions is correct  the model provides.