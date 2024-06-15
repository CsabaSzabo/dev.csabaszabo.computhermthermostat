# Computherm Thermostat

Controls Computherm thermostats. It uses [node-broadlink](https://github.com/ThomasTavernier/node-broadlink) as it's main dependency and functionality to communicate with Broadlink devices, like Computherm.

## How to developer

Useful commands:

- Run locally: `homey app run`
- Run a Homey App in development mode without keeping your command-line window open: `homey app install` 
- Publish app: `homey app publish`

## Hysen device full status

- `dif`: room temperature control difference
- `svh`: room temperature set max
- `svl`: room temperature set min
- `adj`: room temp adjust
- `fre`: antifreeze set
- `pon`: power memory


Examples


```
{
  remoteLock: 0,
  power: 1,
  active: 0,
  tempManual: 0,
  roomTemp: 23,
  thermostatTemp: 21.5,
  autoMode: 3,
  loopMode: 3,
  sensor: 0,
  osv: 42,
  dif: 2,
  svh: 30,
  svl: 15,
  roomTempAdj: 0,
  fre: 0,
  poweron: 1,
  unknown: 1,
  externalTemp: 42,
  hour: 20,
  min: 56,
  sec: 29,
  dayofweek: 3,
  weekDay: [
    { startHour: 7, startMinute: 0, temp: 22 },
    { startHour: 8, startMinute: 15, temp: 21.5 },
    { startHour: 12, startMinute: 30, temp: 21.5 },
    { startHour: 12, startMinute: 30, temp: 21.5 },
    { startHour: 18, startMinute: 20, temp: 22.5 },
    { startHour: 19, startMinute: 30, temp: 21.5 }
  ],
  weekEnd: [
    { startHour: 8, startMinute: 0, temp: 22 },
    { startHour: 23, startMinute: 0, temp: 15 }
  ]
}
```
