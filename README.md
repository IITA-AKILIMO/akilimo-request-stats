# AKILIMO requests downloader

#### This Utility downloads application requests from the `AKILIMO` api

## Features

- Download `Json` data as `text/json` from an endpoint and save it as a file
- Parse json into a `dataframe`


## Tech

This tool uses a number of open source projects to work properly:

- [R](https://www.r-project.org/) - The ultimate statistical tool!


## Sample data



```json
    {
      "id": 1,
      "requestDate": "2021-04-28T12:09:53",
      "deviceToken": "",
      "countryCode": "NG",
      "lat": 6.115468,
      "lon": 7.442762,
      "fullNames": "John Doe",
      "genderName": "NA",
      "gender": "NA",
      "phoneNumber": "254",
      "userType": "EA",
      "useCase": "FR",
      "createdAt": "2021-04-28 12:09:53",
      "updatedAt": "2021-04-28 09:09:53"
    }
```

## Setup

Sensitive information such as passwords are storrend in an environment file `.env` refer to ther `.env.example` for required variable names

## License

MIT