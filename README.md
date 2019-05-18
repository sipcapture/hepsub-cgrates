<img src="https://user-images.githubusercontent.com/1423657/55069501-8348c400-5084-11e9-9931-fefe0f9874a7.png" width=200/>

# hepsub-cgrates
HEP Pub-Sub Client for CGRates

## What?
This HEPSUB agent hooks HOMER 7 with the CGRates API, fetching CDRs, rates and other elements in realtime during session investigation.

## Usage
Once the parameters in `config.js` are prepared, launch the Node application:
#### Manual
```
nodejs cgrates.js
```
#### PM2
```
pm2 start cgrates.js
```

#### Docker
A docker container with the HEPSUB CGrates API is provided for convenience and testing.
```
docker-compose up -d
docker run --name cgrates-hepsub -d sipcapture/hepsub-cgrates
```

## Node API
See `/app` folder
