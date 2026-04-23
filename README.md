# Korean Map pack for Subway Builder
Korean Map Pack(KMP) is a map mode for Subway Builder with Real-world demand maps for 9 Korean cities, built from national transport and population statistics.

## Supported Cities
| City | 도시 | Sizes |
|------|------|-------|
| Seoul | 서울 | 30km, 40km |
| Incheon | 인천 | 30km, 40km |
| Busan | 부산 | 30km, 40km |
| Daegu | 대구 | 30km, 40km |
| Daejeon | 대전 | 30km, 40km |
| Gwangju | 광주 | 30km, 40km |
| Sejong | 세종 | 30km, 40km |
| Ulsan | 울산 | 30km, 40km |
| Jeju | 제주 | 30km, 40km, Full island |

## Features
- **Sub-500m population placement** using Korea's national 500m population mesh
- **Commuter demand from KTDB** — origin-destination statistics from the Korea Transport Database, capturing real-world commute flows between traffic analysis zones
- **Road network routing** using actual Korean road centerline data, producing realistic driving paths between residential and employment points
- **Three-tier administrative labels** with English romanization
  - 시도 (Si, Do - Metropolitan / Provincial level)
  - 시군구 (Si, Gun, Gu - City / County / District level)
  - 읍면동 (Eup, Myeon, Dong - Neighborhood level)
- **Add Special Demands** - Airport, HSR, Bus Terminal, University, Hospital

## Methodology
- Resident and commuter totals are approximated using KTDB traffic analysis zone data, spatially disaggregated via 500m population mesh grids to achieve sub-zone point placement.
- OD pairs are ranked by total trip volume, and driving paths are computed via A routing on the national road network.

## Primary Data Sources
- Korean Transportation Database (Korea Transport Institute, KOTI) (ktdb.go.kr)
- V-world (Ministry of Land, Infrastructure and Transport, MOLIT) (vworld.kr)
- Statistical Geographic Information System (SGIS) plus (Ministry of Data and Statistics, MODS) (sgis.mods.go.kr)
- Address-based Industry Support Service (Ministry of the Interior and Safety, MOIS) (business.juso.go.kr)
- Aviation statistics 2025 (Korea Civil Aviation Association, KCAA) (https://www.airportal.go.kr/stats/transport/dashboard.do)
- Korean railroad statistics 2024 (Korea Railroad, KORAIL) (https://railstat.korail.com/statPortal/)
- Korean Public Transportation Database (Korea Transportation Safety Authority, KTSA) (https://www.kotsa.or.kr/ptc/)
- Korean Hospital and Pharmacy Status (Health Insurance Review and Assessment Service, HIRA) (https://www.data.go.kr/data/15051059/fileData.do)
- Health Insurance Medical Statistics (Health Insurance Review and Assessment Service, HIRA) (https://opendata.hira.or.kr/op/opc/olapHthInsRvStatInfoTab17.do)
- Academy Information System (Ministry of Education, MOE) (https://www.academyinfo.go.kr/index.do)

---

## Issues/Questions
- Please notice me any suggestions and any issues to me using [Discord Channel](https://discord.com/channels/1420846272545296470/1488123736270831717).

## Further Update Plan
- v0.3.0: Add Minor Cities | Suwon, Cheongju, Changwon is now planned.
- v0.4.0: Minor POI Demand | Adding more POI demand to each map, including parks, leasuire points, etc.
- v0.5.0: Add Metropolitan Map | Busan Metropolitan (include Ulsan, Changwon), Daejeon Metropolitan (include Sejong, Cheongju)

## Further Plan
- Add Seoul Metropolitan
