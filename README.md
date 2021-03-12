# SpaceX launch data
SpaceX launch data in a machine readable format (json). Data is based on https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches

## Get data
Use this data in your application with
```
// javascript
data = fetch('https://raw.githubusercontent.com/jacobkjaersgaardhansen/spacex/main/launches.json')
  .then(res => res.json());
  
console.log(data);
// expected output: [{ mission_name, launch_time_utc, ... }, { mission_name, launch_time_utc, ... }, ...]
```
## Examples of applications using this data
https://observablehq.com/@jacobkjaersgaardhansen/spacex-yearly-launches-by-days-elapsed

## Contribute
Pull requests with updated data based on reliable sources are very welcome
