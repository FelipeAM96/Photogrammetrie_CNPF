Link to UAVArenaCPNF : https://felipeam96.github.io/UAVArenaCNPF/

![image](https://github.com/FelipeAM96/UAVArenaCNPF/blob/master/Ecran.jpg)


## About

This repository exists to give the user a comparision  of drone mapping software results compared side by side.

Currently, comparision consists of Orthophoto and DSM only. 

## Methodology

The results are processed for each software using “medium quality”.

## Contributing

run ` python -m http.server 8080 ` from the project root, then open a web browser, if you want to view this project locally. this action requires `Python3`.

If you want to add a new dataset, simply add the relevant folders in the `data` directory, edit `main.js`. The tiles can be generated using the instructions in `tile_commands.txt`.

## Disclaimer

While this is a neutral zone for evaluating the results of drone mapping software and we have performed processing following 
the same standards / quality settings for all solutions.

This application was developed by [ODM](https://github.com/OpenDroneMap/ODM) contributors.
