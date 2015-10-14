# nps-gtfs

A repository of General Transit Feeds Specification (GTFS) for National Park Service transit systems.

Feeds are organized according to the system of `/[alpha_code]/[system_name]/gtfs.zip`.

## Index

- Rocky Mountain National Park: `romo`
  - Shuttle Bus Routes: `shuttles`
- Cuyahoga Valley National Park: `cuva`
 - Cuyahoga Valley Scenic Railroad: `scenic-rail`
- Boston Harbor Islands National Park: `boha`
 - Harbor Islands Ferries: `ferries`*

`boha/ferries`: Certain routes that are part of the Boston Harbor Islands Ferries are shared with and operated by the Massachusetts Bay Transportation Authority (MBTA), the Boston area's public transit agency and operator of regional commuter ferries. These routes are not included in the NPS feed. Developers should ensure they also incorporate the [MBTA's GTFS feed](http://www.mbta.com/rider_tools/developers/default.asp?id=21895) in order to fully reflect the Harbor Islands Ferries schedule.

## Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
